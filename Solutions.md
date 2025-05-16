#####
###### 13. Discuss different types of prototyping. #board_2018 
> Prototyping is a key approach in software development where early versions of a system or its components are built to understand requirements, test functionalities, and gather user feedback. Based on the purpose and nature of the project, different types of prototyping methods are used. These are discussed below:
> 
> 1. **Throwaway Prototyping (Rapid Prototyping)**: In throwaway prototyping, a quick and temporary model of the software is built to understand unclear or incomplete requirements. This prototype is used mainly for demonstration and requirement gathering purposes. Once the feedback is collected, the prototype is discarded, and the final system is developed from scratch. It helps reduce misunderstandings early on, but the work done on the prototype is not reused in the final product.
> 2. **Evolutionary Prototyping**: In evolutionary prototyping, the prototype is not discarded but instead gradually refined based on user feedback. The system is built in a step-by-step manner, and new features are added or improved continuously until it becomes the final product. This approach is ideal for projects where requirements are expected to evolve over time. It ensures better alignment with user needs, but can become complex to manage as the system grows.
> 3. **Incremental Prototyping**: Incremental prototyping involves breaking the overall system into smaller modules and developing prototypes for each module independently. These module prototypes are then integrated to form the complete system. This approach allows developers to focus on one feature at a time and makes it easier to test and improve specific parts of the application. It is particularly useful for large-scale projects where different components can be developed in parallel.
> 4. **Extreme Prototyping**: Extreme prototyping is primarily used in web-based application development. This type of prototyping emphasizes rapid UI development and quick user feedback. It follows a structured three-phase approach to ensure that the user interface and interaction meet the desired requirements before full backend integration.
> 	1. **Phase 1: Static HTML Mockup**: The first phase involves creating a simple, static HTML mockup of the user interface. This mockup focuses purely on the visual aspects of the design and does not include any functionality or dynamic content.
> 	2. **Phase 2: Functional Prototype with Simulated Data**: The static mockup is converted into a functional prototype, where interactions are simulated, but no real data is processed. This gives users a preview of the app's behavior.
> 	3. **Phase 3: Backend Integration**: The prototype is integrated with a real backend, enabling live data processing and turning the prototype into a fully functional application for testing.
> 

---
  
###### 14. What software engineering process? #board_2016
> The **software engineering process** is a structured approach to software development aimed at producing high-quality software. It involves a series of stages, each focused on a specific aspect of software creation.
> 1. **Project Planning and Feasibility Study**: This phase involves assessing the project's scope, cost, timeline, and resources. Feasibility studies are conducted to determine whether the project is technically, financially, and operationally viable.
> 2. **Requirement Analysis**: In this phase, the requirements of the software are gathered from stakeholders and analyzed to understand what the software must do.
> 3. **System Design**: Based on the requirements, the system's architecture and components are designed, including the user interface, database, and software modules.
> 4. **Implementation (Coding)**: The actual code for the system is written, following design specifications and coding standards.
> 5. **Testing**: After coding, the software undergoes various tests (unit, integration, system) to identify and fix defects and ensure it meets the requirements.
> 6. **Deployment**: The software is deployed to users, installed, and configured in the production environment.
> 7. **Maintenance**: After deployment, the software is maintained by fixing issues, improving performance, and updating features based on user feedback.

----

###### 15. Write down the umbrella activities of software engineering. #board_2021 #board_2020 #board_2018     
> Umbrella activities in software engineering support the main development processes and ensure that the project is completed successfully. These activities are ongoing throughout the software development lifecycle and help maintain project quality, control, and progress.
> 
> The activities of umbrella activities are discussed below:
> 1. **Software Project Tracking and Control**: This activity involves monitoring and managing the progress of the software project to ensure that it stays on schedule, within budget, and meets project goals. It includes tracking milestones, progress reports, and adjusting plans as needed.
> 2. **Risk Management**: Risk management focuses on identifying, analyzing, and mitigating potential risks that could affect the success of the software project. It helps prevent major issues and ensures that risks are proactively handled to minimize their impact.
> 3. **Software Quality Assurance (SQA)**: SQA involves activities to ensure that the software meets the required quality standards. This includes planning and conducting reviews, audits, inspections, and testing to verify that the software is reliable, secure, and performs as expected.
> 4. **Formal Technical Reviews**: These reviews involve structured assessments of the software design, code, and other project artifacts. They are conducted by a team of professionals, helping to identify defects early, improve quality, and ensure that the software meets its requirements.
> 5. **Software Configuration Management**: Configuration management involves tracking and controlling changes in the software and its related documentation. This ensures proper version control, enables traceability of changes, and maintains consistency across different parts of the software.
> 6. **Document Preparation and Production**: Creating and maintaining thorough documentation is essential throughout the software development process. This includes documenting requirements, design decisions, code, and test results, ensuring that the software is maintainable and understandable in the future.
> 7. **Reusability Management**: Reusability management encourages the development of software components that can be reused across different projects or modules. This helps reduce development time and effort by leveraging existing, tested components.
> 8. **Measurement and Metrics**: This activity involves defining and collecting metrics related to software development. It helps track the quality of the software and the efficiency of the development process. Metrics such as defect density, code complexity, and test coverage are commonly used.
> 9. **Project Management**: Project management encompasses planning, organizing, and overseeing the execution of the software project. It ensures the project stays on track by managing resources, schedules, budgets, and stakeholder communication, facilitating the successful completion of the project.
> 10. **Verification and Validation (V&V)**: Verification and validation activities ensure that the software is developed according to specifications and fulfills user requirements. Verification checks if the software was built correctly (i.e., according to the design), while validation ensures the right product is built (i.e., meeting user needs and expectations).

![[umbrella-activity.webp]]

---

###### 16. Briefly describe each step of software development life cycle. #board_2016 
> **SDLC** stands for **software development life cycle**. SDLC is a process followed for a software project, within a software organization . It consists of a detailed plan describing how to develop, maintain, replace, and alter or enhance specific software. The life cycle defines a methodology for improving the quality of software and the overall development process. There are **seven main phases** in SDLC:
> 
> 1. **Planning**: This is the first and one of the most important steps. The main goal is to understand what the software is supposed to achieve. The team discusses project goals, budget, required resources, and sets deadlines. Risks are also identified in this phase so that they can be handled early. A proper plan is created which guides the entire development process.
> 2. **Requirement Analysis**: In this phase, detailed information is gathered from stakeholders, clients, and users to understand what the software must do. Both functional (what the software should do) and non-functional (performance, security, etc.) requirements are collected and documented in a Software Requirement Specification (SRS) file. This document is a reference for the next phases.
> 3. **Design**: Here, the software’s structure is planned based on the requirements. Designers create High-Level Design (HLD) for the system’s architecture, and Low-Level Design (LLD) for individual modules and components. It includes database designs, user interface design, and how different parts of the software will work together. This blueprint ensures everyone is on the same page before coding starts.
> 4. **Development**: This is the coding phase where software developers write the actual code using suitable programming languages and tools. Tasks are usually divided among front-end, back-end, and database developers. Everyone follows coding standards to ensure the code is clean and understandable. At the end of this phase, the software is functional and ready for testing.
> 5. **Testing**: Once the development is complete, the software is tested to check for bugs, errors, and to make sure it works as expected. Different types of testing are done such as unit testing (for individual parts), integration testing (how parts work together), performance testing, and security testing. Any issues found are fixed, and the software is retested.
> 6. **Deployment**: After successful testing, the software is delivered to the users. It may first be released as a beta version to a small group for feedback. Based on that feedback, improvements are made before the full release. Once the final version is ready, it is installed on the user’s systems or made available online.
> 7. **Maintenance**: This is the longest phase and continues after the software is released. It includes fixing bugs that users find, updating the software to stay compatible with new technologies, and adding new features when needed. Regular maintenance keeps the software reliable and useful in the long term.

![[SDLC1.jpg]]

---

###### 17. Explain incremental software process model with merits and demerits. #board_2022 #board_2020 #board_2018 
>

---
smaller modules and developing prototypes for each module independently. These module prototypes are then integrated to form the complete system. This approach allows developers to focus on one feature at a time and makes it easier to test and improve specific parts of the application. It is particularly useful for large-scale projects where different components can be developed in parallel.

sdfsdf