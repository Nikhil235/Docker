# Docker
What is Docker ? and why ?

Docker is a container technology : ( A tool for creating & managing containers )

Container -> A standardized unit of software
          -> A package of code and dependencies to run that code ( e.g. Node.js code + node.js Runtime )
         
          1. The Same container always yields the exact same applications and execution behavior ! No matter where or by whom it might be executed.
          
          2. Support for containers is built into modern opertating systems.
          
          3. Docker simplifies the creation and management of such containers.

# What are containers ?

(containers => lightweight| portable | isolated software environment)

- Allow developers to run and package applications with their dependencies, consistently across different platforms.

Help to streamline - **application developement | deployment | and management processes** while ensuring that applications run **consistently**, regardless of underlying infrastructure

## How do containers work?

---

(Containers => (**_Host Operating system + leverage lightweight virtualization techniques_**)

- **_to create isolated process_**)

**_1.Efficiency_**

=> Containers have less overhead and can share **common libraries and executable files** making it possible to run more containers on a **single host** compared to **virtual machines**.

**_2.Portability_**

=> Containers encapsulates applications and their dependencies, so they can easily be moved and run across different environment and platforms consistently.

**_3.Fast Startup_**

=> Containers don't need to boot a full operating system, they can startup and shutdown mcuh faster than virtual machines.

**_4.Consistency_**

=> Containers provide a consistent environment for development, testing and production stages of an applications, reducing the problem.

**_Docker_** -> Simplifies the processes of creating, deploying and managing containers.

## Need for containers

Before containers, Developer faced challenges when deploying applications.

---

**_1.Inconsistent Environments_**

Different environment which might different configuration and libraries compared to production servers.
Leads to compatibility issues in deploying applications.

**_2.Inefficient resource utilization_**

Virtual machines used to overcome environment inconsistency.
Virtual machines requires an entire Operating system to be running for each applications, making resources utilization inefficient.

**_3.Slow processes and scalability issues_**

Traditional deployment method have a slower time to market and scaling difficulties, which hinders fast delivert of software updates.
