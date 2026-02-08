# Assignment 0 – Cynefin Domain Mapping

## Prepared for
**Iles Wade**  
Emerging Trends in Software Development Instructor  
SAIT

## Prepared by
- Bankole, Temiloluwa
- Moyo IV, Terrill
- Hanlon, Christopher
- Singh, Harsimarpreet

## Requested by
**Iles Wade**  
Emerging Trends in Software Development Instructor  
SAIT

**Date:** February 7th, 2026

---

## Part 1: Domain Ownership Assignment
- **Bankole, Temiloluwa → Complicated**
- **Moyo IV, Terrill → Complex**
- **Hanlon, Christopher → Chaotic**
- **Singh, Harsimarpreet → Clear**

---

## Part 2: Domain Research & Authorship
For your assigned domain, write 2 paragraphs describing:  
1. A real-world software development scenario that fits this domain  
2. Why this scenario belongs in this domain (not another)

### Clear
**Original**

**Paragraph 1 – Scenario**  
A clear example of a software development task in the Clear domain is setting up a standard Git workflow for a small development team. The steps are well known: creating a repository, defining a main branch, using feature branches, committing code regularly, and pushing changes to a shared remote repository. These steps are commonly taught in software programs and are widely used across the industry. There is very little uncertainty involved, and developers can follow documented guidelines to complete the task correctly.

**Paragraph 2 – Why it fits Clear**  
This scenario belongs in the Clear domain because the cause-and-effect relationship is obvious. If the correct Git steps are followed, the workflow works as expected. Best practices already exist, and there is no need for deep analysis or experimentation. Unlike complicated or complex problems, this task does not require expert judgment or discovery. It also is not chaotic, since there is no urgency or crisis involved. The correct response is simply to sense the situation, categorize it as a known problem, and apply established best practices.

**AI‑refined**

**Paragraph 1 – Scenario (refined)**  
A strong example of a Clear-domain software development task is implementing a standard Git workflow for a team project. This includes initializing a repository, creating a main branch, using feature branches for development, committing changes with clear messages, and pushing updates to a shared repository. These steps are clearly defined, well-documented, and consistently used in both academic and professional environments. Developers do not need to make assumptions or experiment, as the process is already proven and repeatable.

**Paragraph 2 – Why it fits Clear (refined)**  
This scenario fits the Clear domain because the relationship between actions and outcomes is direct and predictable. When established Git best practices are followed, the result is a clean and functional version control system. There is no ambiguity that would require expert analysis, experimentation, or immediate crisis response. Unlike complicated or complex domains, there are no unknowns to resolve. The appropriate approach is to sense the situation, categorize it as clear, and respond by applying existing best practices.

---

### Complicated
**Original**

**Paragraph 1 – Scenario**  
A complicated example in relation to software development is setting up Role-based access control (RBAC). The set up includes an admin assigning individual users to one or more roles. In this process, different roles represent different permissions for each user. This process is important because it determines user access rights, simplifying tasks like updating job functions, transforming business operations, and helping employee organizations. Additionally, the policies are a big help on cybersecurity vulnerabilities by enforcing the least privilege principle; this means, users have the minimum level of access to fulfill a job.

**Paragraph 2 – Why It Fits**  
This scenario belongs in the complicated domain because there can be difficulty managing highly granular permissions. There can be the accumulation of unnecessary permissions causing more vulnerabilities. This is called role explosion and permission creeps and it happens in large organizations where too many roles become more inconvenient. Moreover, there are four separate models for implementing RBAC making it very perplexing.

**AI‑refined**

**Paragraph 1 – Scenario (refined)**  
A complicated example in software development is implementing Role-Based Access Control (RBAC). This setup involves an administrator assigning individual users to one or more roles, where each role defines a specific set of permissions. RBAC is important because it determines user access rights and simplifies tasks such as updating job functions and managing changes in business operations. Additionally, RBAC policies improve cybersecurity by enforcing the principle of least privilege, ensuring that users are granted only the minimum level of access required to perform their roles.

**Paragraph 2 – Why It Fits (refined)**  
This scenario belongs in the complicated domain because managing highly granular permissions can be difficult and requires expert analysis. Over time, unnecessary permissions may accumulate, increasing security vulnerabilities—a problem known as role explosion and permission creep. This commonly occurs in large organizations where the growing number of roles becomes difficult to manage and maintain. Additionally, the existence of multiple RBAC implementation models adds further complexity, requiring careful evaluation to determine the most appropriate approach.

---

### Complex
**Original**

**Paragraph 1 – Scenario**  
The team is releasing a new feature that recommends study paths based on how students click, search, and complete tasks. Because this is a new market with different study habits, they start with a small pilot group, monitor usage, and adjust the recommendations after each release. They also gather interviews and support tickets to understand why students accept or ignore suggestions.

**Paragraph 2 – Why it fits Complex**  
This fits the Complex domain because cause and effect are not clear in advance and only become visible after observing real behavior. No amount of upfront analysis can predict how diverse learners will respond, so the team must run safe‑to‑fail experiments, sense patterns, and adapt. It is not merely complicated, because there is no single correct expert solution, and it is not chaotic because the team can still take measured steps rather than crisis response.

**AI‑refined**

**Paragraph 1 – Scenario (refined)**  
The team launches a study‑path recommendation feature that adapts to student clicks, search terms, and time‑on‑task. Since it is entering a new market with unfamiliar learning habits, they roll out to a small cohort, run A/B tests, and use analytics plus interviews to refine the recommendation logic over several iterations.

**Paragraph 2 – Why it fits Complex (refined)**  
This belongs in the Complex domain because outcomes emerge from interactions among students, content, and incentives that cannot be reliably predicted upfront. The appropriate response is to probe with safe‑to‑fail experiments, sense the results, and respond by evolving the feature as patterns become visible. Unlike the complicated domain, there is no single best practice to apply; unlike the chaotic domain, the team can still learn and stabilize through iterative feedback.

### Chaotic

**Paragraph 1 – Scenario**

An example of the chaos Cynefin domain in software development would be a major infrastructure issue causing everything to go offline and not work such as an AWS outage if we are using that to host our Web App. This scenario would necessitate immediate action to avoid unnecessary loses. The cause of the situation would not be immediately clear as from our perspective likely all we would know at the start is that our web app is down. To get to a solution you would likely need to use a temporary solution to fix the immediate issue and then need to come up with a permanent fix afterwards.

**Paragraph 2 – Why it fits**

This scenario fits in with the chaos quadrant because it would require an urgent resolution to avoid company losses. Organizing a team and putting together a structured plan to discover the root cause would likely be required depending on the size of the web app. The solution would need to be tiered, there would need to be a quick solution to make the web app functional in the mean time, but then a final solution would need to be made to prevent this issue from occurring in the future.

**AI-refined**

**Paragraph 1 – Scenario (refined)**

An example of the chaotic Cynefin domain in software development is a major infrastructure failure that causes a system-wide outage, such as an unexpected AWS service disruption hosting a web application. In this situation, there is no immediately apparent cause—from the team’s perspective, the only clear signal is that the application is down. The priority is not analysis but rapid action to restore stability and prevent further losses. Teams must act decisively, often implementing temporary or improvised solutions to bring the system back online. Only once stability is regained can the underlying causes be investigated and a permanent fix designed.

**Paragraph 2 – Why it fits (refined)**

This scenario belongs in the chaotic Cynefin domain because it demands immediate action to prevent significant business losses, leaving little to no time for structured analysis. At the outset, there is no clear understanding of the root cause—only the visible impact that the web application is unavailable. Attempting to first organize a team or follow a detailed investigative plan would delay recovery and increase risk. Instead, the priority is to act quickly to restore functionality, often through temporary or ad hoc measures. Once stability is re-established, the situation can then be reassessed to identify the underlying cause and implement a long-term solution to prevent recurrence.


## Visual Component


## Part 3: Team Reflection

When reflecting on the process of working together we decided to collaborate over Microsoft Teams for communication purposes. We worked as a group on a shared Google Docs sheet, which allowed us to see each other’s contributions in real-time. Then simply when it came to dividing tasks, we chose a domain that suited our interests. In preparation for submission, we had one group member step up and tackle the submission and another group member prepare the files that we need for the format of the submission on GitHub. 

Through this exercise, the team was very open and communicative. The group was great to work with because we each spoke out whenever we had questions or uncertainties, and actively worked together to find solutions and complete the task.

From the perspective of the Clear domain owner, the structure of this assignment made the work very straightforward. Working alone on the Clear domain reflected the nature of clear problems themselves — there was little ambiguity, and existing best practices guided the solution. They did not need extensive discussion with the team, which reinforced the idea that not all problems require collaboration to move forward effectively.

From the perspective of the Chaotic domain owner, the most difficult part was coming up with a situation that required a quick action, but is not so straightforward that there is not much to resolve at the end. The discussions with the team helped in coming up with a good situation and understanding why it fit in the domain.

Observing the other domains highlighted how different the experiences were. The Chaotic domain required more discussion and coordination, while the Complex domain involved exploration and multiple viewpoints. This contrast helped the team to better understand how problem types influence teamwork and decision-making. Overall, the Cynefin framework helped clarify when to act quickly, when to analyze deeply, and when to rely on established patterns, which will be valuable during future sprint work.

