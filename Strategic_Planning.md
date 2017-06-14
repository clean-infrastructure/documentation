##  What We Believe

1. Public cloud IaaS and PaaS represent the future of infrastructure ... and the present.

2. The ability to build and deploy stable, secure and resilient infrastructure is critical to innovation.

3. Stable, secure and resilient infrastructure is impossible without robust automation.

4. Most infrastructure problems that exist today are common across all organizations implementing cloud infrastructure.

5. These problems can and should be solved once, the right way, and reused by many.

6. Every organization should have access to world-class infrastructure code regardless of their size or expertise.

## Why Us

Together, our team represents a broad spectrum of infrastructure and software engineering expertise.

We've designed and run mission-critical, high performance and secure cloud infrastructures for some of the largest technology organizations in the world.

We have the expertise, practical experience and ability to address this problem. No one else is doing this in a community-driven manner or offering solutions to these problems without commercial strings attached.

## How We Do It

The first phase of developing our initiative will have three distinct pillars of work:

1. **Media Presence**

   This work will be crucial to garnering community involvement, establishing partnerships and ensuring positive exposure of our initiative.

   This work will include development of our web presence, graphic design and managing our social media presence.

2. **Patterns and Practices**

  This work is where developing our solutions begins to include designing robust architecture diagrams and documenting the best-practice principles behind core design decisions.

  The output of this work will form the foundational documentation and requirements for each module.

3. **Development**

  Includes the development and testing of the core modules that implement the architectures and best-practice principles produced above.

Initially, our focus will be on building solutions for AWS and implementing those solutions using [Terraform](https://www.terraform.io/).

At later stages, we will branch out into other public cloud providers such as Azure, GCE, GKE and possibly others.

## Initial Solutions

Within the architecture and development work pillars, the first phase should focus on building a secure and reliable foundation on whcih to build additional infrastructure.

This will include:

- Bootstrapping of AWS accounts to include account-wide policies and configurations.

- A secure IAM strategy that adheres to the least-privilege principal.

- A secure VPC architecture that isolates and secures traffic while providing resiliency and flexibility.

- A hardened bastion infrastructure that provides secure management access to infrastructure components.

- In addition to architecture diagrams and documented best-practices, we will need example documentation that shows how to implement the components together to build production-ready infrastructure.

## Guiding Principles

This project starts with the premise that infrastructure code should be given the same care and attention as any other software development discipline.

Clean code matters. Every infrastructure module we develop should adhere to the following principles:

- **If it isn't documented, it doesn't exist.**

  Design comes before coding. Every module and every decision made must be backed by well documented best-practice principles and robust, easy to understand architecture diagrams.

- **Code quality counts.**

  Reading our modules should be a pleasant experience. Code needs to be well organized, narrowly focused, cleanly separated and thoroughly commented.

- **Everything is tested.**

  Every module must be backed by a suite of comprehensive and automated unit and acceptance tests. This means we can validate that our code complies with the design requirements and we can maintain and extend it without worrying that it will stop working.

- **Customizable and Configurable.**

  Our modules should have thoroughly documented input variables that allow users to easily customize and configure their behavior.

  Every module should include robust outputs giving users a highly composable system of modules that can be pieced together to build comprehensive infrastructures.

- **The master branch works. Period.**

  Isolate development work from master using feature branches, then merge to mainline once everyone is happy with them. All changes should be merged with a well documented merge request, updated README and CHANGELOG and only after peer review.

- **Critique code instead of people – be kind to the coder, not to the code.**

  Good peer review is what makes better design decisions. As much as possible, make all of your comments positive and oriented to improving the code. Relate comments to coding standards, feature specs, increased performance, functionality, etc.

- **You are not your code.**

  Understand and accept that you will make mistakes. Remember that the entire point of a review is to find problems, and problems will be found. Don’t take it personally when one is uncovered.

- **Mature engineers seek out constructive criticism. Beg for the bad news.**

  No matter how much "karate" you know, someone else will always know more. Seek and accept input from others.

  Nothing you make on this project will ever only be in your hands. What could you be missing? How will this not work. Even if your idea is technically sound, is it understandable enough for others to operate, troubleshoot and extend?
