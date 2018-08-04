# Introduction

During the process of software development, it is necessary to take into account the interests of several groups of participants: business customers, designers, testers, and developers. One specific feature of mobile business applications is their low complexity in comparison to corporate backend-services. They entail a minimum of business logic \(it's all on the server\), and almost always have a static and relatively simple interface. 

From our experience, most mobile development teams face the following problems during the long-term development of a project:

1. The absence or non-observance of architectural patterns, which leads to a chaotic arrangement of files in the structure of the solution. Also, unnecessary connections between classes and subsystems are created. All this complicates and slows the development of the product, as it takes a lot of time to unravel the "noodles."
2. The difficulty when working with project documentation is that it takes a lot of reading to create the full picture; the details can still fall out of your head.
3. The lack of a single documentation (except for Requirements and Backlog) for the whole team, which would be pretty compact and accessible, while at the same time making it easier to find a common language. "Documentation separately, code separately" - names from the documentation used in the code rarely, which complicates its development and progress.

In our guide we will describe a step-by-step process of preparing technical documentation that will allow you to _create a "skeleton" for the project based on the user interface_. We will also focus on the necessary minimum of electronic documents on which the team members can rely in the future.

Questions that we will try to answer in this guide:

1. **How to expand the project documentation so that it is easier for the developer to prepare the project structure by himself or herself?**

2. **How to organize team interaction on the basis of a single technical documentation?**

3. **How to use the technical documentation as a checklist?**

Our guide is aimed at a wide range of mobile application developers and software engineers. In general, the described approach, with small modifications, can be applied for software design of any classes of applications with a user interface: web, desktop and embedded. However, it can be redundant for small projects \(less than 10 screens\), as it was created for large applications \(from 40 screens\).

We really hope that the approach described in the guide will allow you and your colleagues to speed up the release of quality products due to more efficient work with documentation. 

Enjoy reading!