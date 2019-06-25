# 25. Software Development Lifecycle Policy

To create and deliver high quality business information systems that align with current Cloudticity vision and business objectives, meet or exceed customer expectations when promised and within cost estimates, and work effectively and efficiently within the current and planned information infrastructure; Cloudticity has established a Software Development Life Cycle (SDLC) framework, and related software application development methodologies and tools that are essential components in the management, development, and delivery of software applications to support business needs and services. This policy applies to all Oxygen product development regardless of deployment to internal or customer-facing environments.

## 25.1 Applicable Standards

### 25.1.1 Applicable Standards from the HITRUST Common Security Framework

*  09.ab - Monitoring System Use
*  10.a - Security Requirements Analysis and Specification

## 21.2 Software Development Policy

*Feasibility* - All Oxygen product development must begin with a feasibility and business alignment study. This study must include:
1. Alignment with current Cloudticity vision and business objectives
2. Product development feasibility and impact on existing business operations
3. Study of 3rd party alternatives
4. Detailed description of potential ROI

*Design* – High level concepts and designs must be submitted for approval.  Approval must be obtained by the CEO, COO, and Director of Technology before proceeding. Minimum design requirements include:
1. High level system functionality diagrams describing process flows.
2. High level system architecture diagram showing both customer environments and integrations with Cloudticity production environment
3. Description of system components including individual modules and 3rd party APIs.
4. Potential cost impact on both customer environments and Cloudticity Production environment.

*Build* – Oxygen product development must execute using both industry standards and Cloudticity specific processes and procedures which are intended to deliver consistent, quality results for every delivered product.  Minimum development standards include:
1. All code development must be executed using the following git flow:
a. Changes to code and new features are developed in a feature/bug branch created from the development branch.
b. Local development must adhere to standards specified in the Oxygen Development Standards
c. Once the feature is completed and tested
* Feature branch is merged into development branch executing automated “development” deployment.
* Feature is tested in staging per requirements listing in Testing and Validation of this document.
* A code review is performed to
* * Ensure code requirements are met
* * Review basic code structure and architecture.
* * Review documentation for content and structure
d. Upon successful code and documentation review, a pull request is created for a merge into master
e. A merge into master executes the automated code deployment process

*Testing & Validation* - A proper testing and validation process must be followed for each Oxygen product developed.  The testing and validation process determines the quality and the cost implications of any product before it is deployed.  Minimum standards for testing and validation include:
1. Unit tests must written for at least 98% of methods included in product processes.
2. Testing must ensure that explicit error checking is performed and documented for all input, including for size, data type, and acceptable ranges or formats.
3. Code quality adherence using a standard linter (eslintrc for Node.js) that validates basic syntax and method quality.
4. Code and package security validation using a 3rd party module such as Node Package Manager (NPM).
5. Cost validation by executing product in development environment under baseline operation levels. 
6. Code execution impact on current system validation 
7. High volume (stress test) product execution testing.  Must include test scenarios and baseline metrics.
8. Peer code review.  
9. Final Build Master code review and approval.

*Release Management* – Release management practices are to be applied to all software development lifecycles as well as hardware, documentation, processes, and other components of a service. Release management focuses on strategic planning, scheduling, and controlling the movement of releases between development, staging, and production environments. Release management must follow these steps:
1. Product feature must be merged into the development branch and must pass CI/CD pipelines checks for:
a. Code coverage
b. Lint tests
c. NPM builds
d. Deployment package structure
2. Final code review by Build Master
3. Pull request submitted for master branch
4. Build Master merges code into master branch
5. Administrator approves deployment during CI/CD pipeline execution

*Revisions* - this policy must be reviewed and revised on a Monthly basis.  Review scheduling is executing using recurring tasks in project management platform.