## 🚀 From Junior to Tech Lead to Senior – Real Challenges That Drove My Promotions

🔥 This section includes four key real-world challenges I faced and solved during my journey from a Junior DevOps Engineer to a Tech Lead, and eventually to a Senior DevOps Engineer.

 👉 Each story reflects the ownership, innovation, and impact that contributed to my promotions and leadership recognition.

#### Challenge 1: Saving $200K/Year Cloud Bill with FinOps Automation
#### Challenge 2: Rebuilding and Accelerating 60% Broken CI/CD Pipelines Across 3 Teams

 📝 These challenges represent only a small part of the real challenges I've faced and solved throughout my DevOps career — likely less than 10% of the full journey. I chose them because each directly contributed to my career growth from Junior to Tech Lead, and eventually to Senior DevOps Engineer.

**More real challenges and advanced solutions will be added in future updates to this repository as I continue documenting my real-world experiences.**

 I hope these challenges inspire you to take ownership of your work, innovate within your teams, and strive for excellence in everything you do.

 🔁 Feel free to reach out if you have any questions or would like to discuss any of these challenges in more detail. I'm always happy to connect and share insights with fellow professionals in the field!

> These challenges reflect part of what I documented from my **first 4 years** of hands-on experience. In the coming days, I will share additional challenges — along with more in-depth details. 
> I will continue updating this repo with more challenges from the rest of my career as I find time to review and write them accurately.

## Challenge 1: Saving $200K/Year Cloud Bill with FinOps Automation

**Situation:** At my educational Univeristy, our cloud bill was ballooning to over $650K per year due to unoptimized resources and a lack of visibility into spending. The finance team was frustrated, and the engineering teams were overwhelmed by constant cost-cutting measures.

**Task:** I took ownership of the situation and proposed implementing a FinOps strategy to gain visibility and control over our cloud expenses. My goal was to automate cost optimization processes and create a culture of financial accountability within the engineering teams.

**Action:** I collaborated with stakeholders from finance, engineering, and product teams to establish a FinOps framework. We implemented automated cost monitoring tools that provided real-time insights into resource usage and spending patterns. I also developed custom dashboards that allowed teams to visualize their cloud costs in relation to their projects. 
- Finally, we discovered that some actions needed to be taken immediately — 73 engineers across all teams were using Azure test licenses, while only tech leads and managers actually needed them. 
- I also found that, during CI/CD runs, Azure charges build minutes, and the repo history was very long — around 8 years. So, I suggested archiving the main repo and keeping only the last year of history for active development.
- In addition to that, I noticed that AWS EC2 dev machines were running 24/7, so I automated their shutdown at the end of each workday.

**Result:** Within six months, we reduced our cloud bill by 30%, saving the company over $200K annually. The finance team was thrilled with the improved visibility, and the engineering teams felt empowered to optimize their resources without fear of sudden budget cuts. This initiative not only earned me recognition but also contributed significantly to my promotion to Tech Lead.

## Challenge 2: Rebuilding and Accelerating 60% Broken CI/CD Pipelines Across 3 Teams

**Situation:** At one point, our CI/CD pipelines were unreliable, causing frequent build failures and deployment delays. Three different teams were using disparate tools and processes, leading to confusion and frustration.

**Task:** I recognized that this situation was hindering our ability to deliver software quickly and efficiently. I took it upon myself to standardize our CI/CD processes across all three teams while ensuring minimal disruption to ongoing development work.

**Action:** I organized workshops with each team to gather feedback on their current processes and pain points. Based on this input, I proposed a unified CI/CD pipeline using Azure DevOps as a connected platform that integrates all discipline tools as our standard. I wrote comprehensive documentation and created reusable templates for common tasks, making it easier for teams to adopt the new system.

- As a result, I suggested using a GitFlow branching and merge strategy instead of the existing trunk-based model, which required a higher level of team maturity and coordination. So, that any new feature would be tested separately — including integration tests — before being merged. This kept the main branch clean, containing only integrated and production-ready features. 

- In addition, I restructured the DevOps architecture to maintain a clean pipeline from artifact storage in CI all the way to deployment on pre-created infrastructure — using a dedicated build account to ensure full traceability and immutability. 

- Previously, anyone could edit infrastructure configurations with no traceability, leading to a lack of accountability.

**Result:** The new standardized CI/CD pipelines reduced build times by 60%, increased deployment frequency, and ensured the infrastructure remained immutable.


