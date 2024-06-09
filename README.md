[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/-ucQIGTc)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15243855&assignment_repo_type=AssignmentRepo)
# SE-Assignment-2
Assignment: Introduction to Software Engineering
Instructions:
Answer the following questions based on your understanding of software engineering concepts. Provide detailed explanations and examples where appropriate.

Questions:
Define Software Engineering:
software engineering as an engineering branch associated with the development of software product using well-defined scientific principles, methods and procedures.
It can also be defined (According to IEEE) as;
The application of a systematic, disciplined, quantifiable approach to the development, operation and maintenance of software.

What is software engineering, and how does it differ from traditional programming

Software engineering is an engineering discipline that is concerned with all aspects of software production.Software engineering involves advanced computer science and engineering skills that include programming  while programming focuses solely on software coding.

Software Development Life Cycle (SDLC):

Explain the various phases of the Software Development Life Cycle. Provide a brief description of each phase.

A software life cycle model (also called process model) is a descriptive and diagrammatic representation of the software life cycle. A life cycle model represents all the activities required to make a software product transit through its life cycle phases. It also captures the order in which these activities are to be undertaken.
The SDLC typically includes the following phases:
1. Requirements gathering and analysis: This phase involves gathering information about the software requirements from stakeholders, such as customers, end-users, and business analysts.

2. Design: In this phase, the software design is created, which includes the overall architecture of the software, data structures, and interfaces. It has two steps:

High-level design (HLD): It gives the architecture of software products.
Low-level design (LLD): It describes how each and every feature in the product should work and every component.

3. Implementation or coding: The design is then implemented in code, usually in several iterations, and this phase is also called as Development.

4. Testing: The software is thoroughly tested to ensure that it meets the requirements and works correctly.

5. Deployment: After successful testing, The software is deployed to a production environment and made available to end-users.

 6. Maintenance: This phase includes ongoing support, bug fixes, and updates to the software.

Agile vs. Waterfall Models:
Compare and contrast the Agile and Waterfall models of software development. What are the key differences, and in what scenarios might each be preferred?

Waterfall has a fixed timeline whereas Agile is a lot more flexible and accounts for experimenting with different directions. 

The waterfall model is a linear and sequential model, which means that a development phase cannot begin until the previous phase is completed. We cannot overlap phases in the waterfall model while agile model is a combination of iterative and incremental models, that is, it is made up of iterative and incremental models.

Scenarios:
Agile suits dynamic projects where requirements evolve.
Waterfall suits Well-defined, stable projects with clear requirements.

Requirements Engineering:

What is requirements engineering? Describe the process and its importance in the software development lifecycle.
Requirements engineering is the process of establishing the services that the customer requires from a system and the constraints under which it operates and is developed.

Step 1- Assigning roles:
The first step is to identify and engage with all relevant stakeholders. Stakeholders can include end-users, clients, project managers, subject matter experts, and anyone else who has a vested interest in the software project. Understanding their perspectives is essential for capturing diverse requirements.

Step 2- Define Project Scope:
Clearly define the scope of the project by outlining its objectives, boundaries, and limitations. This step helps in establishing a common understanding of what the software is expected to achieve and what functionalities it should include.

Step 3- Conduct Stakeholder Interviews:
Schedule interviews with key stakeholders to gather information about their needs, preferences, and expectations. Through open-ended questions and discussions, aim to uncover both explicit and implicit requirements. These interviews provide valuable insights that contribute to a more holistic understanding of the project.

Step 4- Document Requirements:
Systematically document the gathered requirements. This documentation can take various forms, such as user stories, use cases, or formal specifications. Clearly articulate functional requirements (what the system should do) and non-functional requirements (qualities the system should have, such as performance or security).

Step 5- Verify and Validate Requirements:
Once the requirements are documented, it’s crucial to verify and validate them. Verification ensures that the requirements align with the stakeholders’ intentions, while validation ensures that the documented requirements will meet the project’s goals. This step often involves feedback loops and discussions with stakeholders to refine and clarify requirements.

Step 6- Prioritize Requirements:
Prioritize the requirements based on their importance to the project goals and constraints. This step helps in creating a roadmap for development, guiding the team on which features to prioritize. Prioritization is essential, especially when resources and time are limited.

Benefits of Requirements Gathering:
Cost reduction
 When requirements are well-defined and thoroughly understood at the beginning of a project, it minimizes the likelihood of costly changes and rework later in the development process.

 Improved Communication
Requirements gathering serves as a communication bridge between various stakeholders involved in a project, including developers, clients, users, and project managers.

Customer Satisfaction
 When the end product aligns closely with the expectations and needs of the stakeholders, it enhances user experience and meets customer demands.

 Efficient Resource Utilization
 Thorough requirements gathering enables the efficient allocation and utilization of resources.

Software Design Principles:

Explain the concept of modularity in software design. How does it improve maintainability and scalability of software systems?

Modularization is a technique to divide a software system into multiple discrete and independent modules, which are expected to be capable of carrying out task(s) independently. These modules may work as basic constructs for the entire software. Designers tend to design modules such that they can be executed and/or compiled separately and independently.
Modular design unintentionally follows the rules of ‘divide and conquer’ problem-solving strategy this is because there are many other benefits attached with the modular design of a software.

Modularity improves maintainability by enabling targeted updates and scalability by allowing independent growth.
Individual Modules: By dividing a complex software system into smaller, loosely coupled modules, developers can focus on maintaining and updating specific parts independently. This compartmentalization allows for targeted bug fixes and feature enhancements without affecting the entire system.
Independent Scaling: Modular systems allow for individual scalability. When demand increases, developers can scale specific modules without affecting others. This flexibility ensures efficient resource utilization.

Testing in Software Engineering:

Describe the different levels of software testing (unit testing, integration testing, system testing, acceptance testing).

Unit Testing
Unit testing is undertaken after a module has been coded and successfully reviewed. Unit testing (or module testing) is the testing of different units (or modules) of a system in isolation.
In order to test a single module, a complete environment is needed to provide all that is necessary for execution of the module. 

Integration testing
In integration testing, different modules of a system are integrated in a planned manner using an integration plan. The integration plan specifies the steps and the order in which modules are combined to realize the full system. After each integration step, the partially integrated system is tested. The primary objective of integration testing is to test the module interfaces, i.e. there are no errors in the parameter passing, when one module invokes another module.

System testing
System testing is normally carried out in a planned manner according to the system test plan document. The system test plan identifies all testing-related activities that must be performed, specifies the schedule of testing, and allocates resources. It also lists all the test cases and the expected outputs for each test case.

Acceptance testing
 It is the system testing performed by the customer himself after the product delivery to determine whether to accept or reject the delivered product.


 Why is testing crucial in software development?

 The aim of the testing process is to identify all defects existing in a software product. Testing provides a practical way of reducing defects in a system and increasing the users’ confidence in a developed system and ensures that the developed system conforms to its requirements laid out in the SRS document.

Version Control Systems:

What are version control systems, and why are they important in software development? Give examples of popular version control systems and their features.

A version control system is a software tool that helps software teams track and manage changes to source code over time.

Version control systems (VCS) are essential in software development because they:
Track changes in code over time, allowing developers to collaborate, manage code, and maintain a history of changes.
Ensure code integrity, collaboration, and efficient development workflows

Git: Distributed, supports branching, merging, and collaboration.
Subversion (SVN): Centralized, tracks changes, and supports branching.
Mercurial: Distributed, lightweight, and easy to use.

Software Project Management:

Discuss the role of a software project manager. What are some key responsibilities and challenges faced in managing software projects?

The role of a software project manager involves defining scope, managing resources, promoting team communication, and mitigating risks1. Some key responsibilities and challenges faced in managing software projects include;
    Defining project scope
    Creating schedules
    Managing the development team
    Identifying and mitigating risks
    Handling changes in requirements

Software Maintenance:

Define software maintenance and explain the different types of maintenance activities. 

Software maintenance is the process of modifying a software product after delivery to correct faults, improve performance or other attributes, or adapt to a changed environment.

Types of software maintenance;
 Corrective: Corrective maintenance of a software product is necessary to rectify the bugs observed while the system is in use.
 Adaptive: A software product might need maintenance when the customers need the product to run on new platforms, on new operating systems, or when they need the product to interface with new hardware or software.
 Perfective: A software product needs maintenance to support the new features that users want it to support, to change different functionalities of the system according to customer demands, or to enhance the performance of the system.
 
 Why is maintenance an essential part of the software lifecycle?

Ethical Considerations in Software Engineering:

What are some ethical issues that software engineers might face?
Examples of ethical dilemmas in software engineering may include;
a) Disagreement in principle with the policies of senior management.
b) Your employer acts in an unethical way and releases a safety-critical system without finishing the testing of the system.
c) Participation in the development of military weapons systems or nuclear systems.

 How can software engineers ensure they adhere to ethical standards in their work?

Software engineers can be guided by the following principles in order to adhere to ethical standards;
1. PUBLIC - Software engineers shall act consistently with the public interest.
2. CLIENT AND EMPLOYER - Software engineers shall act in a manner that is in the best interests of their client and employer consistent with the public interest.
3. PRODUCT - Software engineers shall ensure that their products and related modifications meet the highest professional standards possible.
4. JUDGMENT - Software engineers shall maintain integrity and independence in their professional judgment.
5. MANAGEMENT - Software engineering managers and leaders shall subscribe to and promote an ethical approach to the management of software development and maintenance.
6. PROFESSION - Software engineers shall advance the integrity and reputation of the profession consistent with the public interest.
7. COLLEAGUES - Software engineers shall be fair to and supportive of their colleagues.
8. SELF - Software engineers shall participate in lifelong learning regarding the practice of their profession and shall promote an ethical approach to the practice of the profession.



Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
