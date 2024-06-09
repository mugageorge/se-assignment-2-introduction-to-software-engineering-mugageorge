[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15222364&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:

Define Software Engineering:

What is software engineering, and how does it differ from traditional programming?

Software engineering involves the design, development, testing, deployment and maintenance of software products. It differs from traditional programming because it involves from planning to maintenance of a software.


Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.
1. Planning and analysis - 
Involves defining the project goals, identifying the target audience and outlining the features and functionalities of the software. A feasibility study is conducted to assess if the project is viable.
2. Defining requirements - 
The information gathered during the planning and analysis phase is converted into clear requirements for development of the software. 
3. Design - 
The software's architecture and user interface are designed which involves creating blueprints and flowcharts to illustrate how the software will function.
4. Development - 
Programmers write the code for the software based on the design specifications.
5. Testing - 
The software is thoroughly tested to identify and fix bugs and ensure it meets the defined requirements.
6. Deployment - 
After debugging, the software is released to the end-users. This may involve deploying the software on a server or making it available for download.
7. Maintenance - 
The software needs to be maintained and updated to fix bugs, address security vulnerabilities and incorporate new features.

References:
https://theproductmanager.com/topics/software-development-life-cycle/


Agile vs. Waterfall Models:

Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

The agile model produces ongoing release cycles, each featuring small incremental changes from the previous release. At each iteration, the product is tested. The agile model is suitable to projects that require constant improvements and need the flexibility to adapt to the varying requirements.

In the waterfall model, each phase phase depends on the outcome of the previous phase and all phases run sequentially. The model provides discipline and gives a tangible output at the end of each phase. The waterfall model is suitable when the project requirements are clear, unambiguous and unlikely to change significantly during development.

References:
https://www.synopsys.com/glossary/what-is-sdlc.html


Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirements engineering is the discipline that involves establishing and documenting requirements. The process of requirements engineering has the following steps:
1. Elicitation - 
Involves gathering information from various sources like users, clients and technical experts to understand their needs, expectations and pain points.
2. Analysis - 
Once requirements are collected, they are analyzed for completeness, consistency and feasibility. Conflicting needs are identified and resolved.
3. Specification - 
Clear and consise documents are created that detail the functional and non-functional requirements of the software. 
4. Validation - 
The documented requirements are ensured to reflect the stakeholders' needs. Stakeholders reveiw and confirm the specifications.
5. Management - 
The requirements are tracked and managed throughout the development process. Changes are documented and communicated to ensure everyone is on the same page.

Requirements engineering is important to the software development life cycle because:
1. It has a clear vision of what the software needs to achieve.
2. Leads to reduced errors.
3. Stakeholders will be satisfied.
4. Leads to the project success.

References:
https://www.studysmarter.co.uk/explanations/engineering/aerospace-engineering/requirements-engineering/


Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Modularity is a fundermental design principle in software engineering aimed at creating software in a way that minimizes dependencies among the components of a system.

Modularity improve maintainability and scalability of software systems in the following ways:
1. Isolating changes of a small feature.
2. Easier debugging.
3. Independent development which reduces conflicts.
4. Easier expansion without rewriting the entire system.

References:
https://www.ituonline.com/tech-definitions/what-is-modularity-in-software-design/


Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing). Why is testing crucial in software development?
1. Unit testing - 
Individual software units are tested in isolation to ensure they work as intended.
2. Integration testing  - 
Modules or components are combine to verify they interact correctly with each other. 
3. Systems testing  - 
The entire software system is tested as a whole to ensure it meets all functional and non-functional requirements.
4. Acceptance testing - 
The sofware is evaluated by the end-users to confirm that it meets their needs and is ready for deployment. 

Testing is crucial in software development because it helps identify and eliminate bugs before they reach the users.

References:
https://www.tuleap.org/software-quality-different-types-software-testing


Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.
Version control systems are a category of software tools that helps in recording changes made to files by keeping track of modifications done in the code. They help the developers to efficiently communicate and manage all changes that have been made to the source code along with the information like who made and what changes have been made.

Examples of version control systems include:
1. Git - 
Allows creating isolated development environments called branches to work on features without affecting the main codebase. The branches can then be merged back in when ready.

2. Subversion (SVN) - 
Supports branching for development but branching is less flexible compared to Git.

References: 
https://www.geeksforgeeks.org/version-control-systems/


Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?
A software project manager is the leader and organizer of a software development project. Its reponsibilities include:
1. Preparing project proposals and discussing potential projects with clients and stakeholders.
2. Facilitating project initiation by defining project scope and requirements and preparing the necessary documents and requirements.
3. Identifing and managing project risks.
4. Facilitating team meetings and collaboration.
5. Ensuring software quality standards are met and requirements are submitted within budget and on time.

A software project manager can face some challenges such as:
1. Clients may add new features or change existing ones mid-development which affect timelines, budget and resource allocation.
2. Tight deadlines can put immense pressure on the project team.
3. Project managers often face limitations on the team size, budget and available tools. 
4. Sometimes shortcuts are taken or corners are cut to meet deadlines which can lead to technical debt where the code becomes messy and difficult to maintain.

References: 
https://project-management.com/project-manager-roles-responsibilities-software-projects/


Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. Why is maintenance an essential part of the software lifecycle?

Software maintenance is the process of changing, modifying and updating the software to keep up with the customer needs. There are different types of maintenance activities:
1. Corrective maintenance - 
Bugs are fixed and errors are resolved to get the software functioning as intended.

2. Adaptive maintenance - 
Ensures the software keeps pace with external changes such as new operating systems, hardware upgrades and new business rules.

3. Perfective maintenance - 
Focuses on improving the software's overall functionality, performance and user experience.

4. Preventive maintenance - 
Potential issues are identified before they cause probems and steps are taken to prevent them.

Maintenance is an essential part of the software development life cycle because it ensures functionality and reliability of the software and enhances its security.

Reference: 
1. https://cpl.thalesgroup.com/software-monetization/four-types-of-software-maintenance#:~:text=Software%20maintenance%20is%20the%20process,to%20boost%20performance%2C%20and%20more.
2. https://radixweb.com/blog/why-software-maintenance-is-necessary


Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face? How can software engineers ensure they adhere to ethical standards in their work?

Some ethical issues that software engineers might face include:
1. Unethical data collection.
2. Algorithmic bias.
3. Weak security. 
4. Wrong priorities.

Software engineers can ensure they adhere to ethical standards in their work by doing the following:
1. Taking proactive measures to address any potential abuse and other ethical issues in software development.
2. Being straightforward and truthful while describing the software to the audience.
3. Avoid making false claims regarding the application that could be deceptive or misleading. 
4. Prioritizing responsibilities as a good citizen over reputation as an expert. 

References:
https://fullscale.io/blog/ethical-issues-in-software-development/


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
