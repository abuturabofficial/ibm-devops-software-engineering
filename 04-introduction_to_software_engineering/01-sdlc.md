<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Overview of Software Engineering](#overview-of-software-engineering)
  - [What is Software Engineering?](#what-is-software-engineering)
  - [Introduction to SDLC](#introduction-to-sdlc)
  - [Phases of the SDLC](#phases-of-the-sdlc)
    - [Phase 1: Planning](#phase-1-planning)
    - [Phase 2: Design](#phase-2-design)
    - [Phase 3: Development](#phase-3-development)
    - [Phase 4: Testing](#phase-4-testing)
    - [Phase 5: Deployment](#phase-5-deployment)
    - [Phase 6: Maintenance](#phase-6-maintenance)
  - [Building Quality Software](#building-quality-software)
    - [Requirement Gathering](#requirement-gathering)
    - [Design](#design)
    - [Coding for quality](#coding-for-quality)
    - [Testing](#testing)
    - [Releases](#releases)
    - [Documenting](#documenting)
  - [Requirements](#requirements)
    - [1) Identifying stakeholders](#1-identifying-stakeholders)
    - [2) Establishing goals and objectives](#2-establishing-goals-and-objectives)
    - [3) Eliciting, documenting, confirming](#3-eliciting-documenting-confirming)
    - [4) Prioritizing](#4-prioritizing)
    - [Requirements documentation:](#requirements-documentation)
- [The Software Building Process and Associated Roles](#the-software-building-process-and-associated-roles)
  - [Software Development Methodologies](#software-development-methodologies)
    - [Waterfall pros and cons](#waterfall-pros-and-cons)
    - [V-shape model pros and cons](#v-shape-model-pros-and-cons)
    - [Agile pros and cons](#agile-pros-and-cons)
  - [Software Versions](#software-versions)
  - [Software Testing](#software-testing)
    - [Three types of testing:](#three-types-of-testing)
    - [Testing levels](#testing-levels)
  - [Software Documentation](#software-documentation)
    - [Types of product documentation](#types-of-product-documentation)
    - [Standard operating procedures](#standard-operating-procedures)
    - [Updating documentation](#updating-documentation)
  - [Roles in Software Engineering Projects](#roles-in-software-engineering-projects)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Overview of Software Engineering

## What is Software Engineering?

- Application of scientific principles for design and creation of software
- Systematic approach to software development
	- Design
	- Build
	- Test

**Software Crisis:**

- Began in mid-1960s
- Resulted from software development that ran over budget and behind schedule with unmanageable and buggy code
- By the time old software solutions were developed, the newer technologies got the traction, and code refactoring would become necessary
- Solutions didn’t scale well to large projects

Engineering principles:
- Resolved as standardized methods in software engineering and computer-aided software engineering (CASE) tools were developed

![](assets/Pasted%20image%2020230520060410.png)

**Software engineer vs. software developer:**

| Engineer                          | Developer                                                                  |
| --------------------------------- | -------------------------------------------------------------------------- |
| Also developers                   | Narrower in scope than SE                                                  |
| Broad, big picture knowledge base | Creative approaches                                                        |
| Systematic development process    | Write code to implement specific functionality and solve specific problems |
| Focus on structure                |                                                                            | 

**SE responsibilities:**

- Design, build and maintain software systems
- Write and test code
- Consult with stakeholders, third party vendors' security specialists, and other team members

**Software Development Life Cycle (SDLC):**

- Scientific approach to software development
- Guides the software development process
- Identifies discrete steps needed to develop software

## Introduction to SDLC

- Systematic process to develop high-quality software
- Aims to produce software that meets requirements
- Defined phases with their own processes and deliverables
- Cycle of planning, design, and development
- Minimizes development risks and costs

**History of the SDLC:**

- Conceived of in the mid-1960s
- A deliberate approach needed to manage complex projects
- Initially used the waterfall method
- Adapted to use iterative methods

**Advantages of the SDLC:**

- Improves efficiency and reduce risks
- Team members know what they should be working on and when
- Facilitates communication among stakeholders
- Team members know when development can move to the next phase
- Respond to changing requirements
- Solve problems early in the process
- Reduces overlapping responsibilities

## Phases of the SDLC

- Organizations may have different names for each stage
- Some organizations have more or fewer stages

![](assets/Pasted%20image%2020230520062101.png)

### Phase 1: Planning

Requirements;
- Gathered
- Analyzed
- Documented
- Prioritized

![](assets/Pasted%20image%2020230520062241.png)

**Prototyping:**

- Small-scale replica to clarify requirements
- Tests design ideas
- Can be developed at various stages of the SDLC

**Software Requirements Specification:**

- Requirements are documented in the SRC
- All stakeholders must agree

### Phase 2: Design

![](assets/Pasted%20image%2020230520062615.png)

### Phase 3: Development

Development starts when the design document is finalized and sent to the developers to write code for it.

### Phase 4: Testing

- Code is tested to ensure stability, security, and that it meets requirements from the SRS
- Bugs reported, tracked, fixed, and retested

Some common tests:
- Unit testing
- Integration testing
- System testing
- Acceptance testing

### Phase 5: Deployment

![](assets/Pasted%20image%2020230520062956.png)

### Phase 6: Maintenance

![](assets/Pasted%20image%2020230520063053.png)

## Building Quality Software

**Common software engineering processes:**

- Requirements gathering
- Design
- Coding for quality
- Testing
- Release
- Documenting

### Requirement Gathering

- The SRS encompasses the process of collecting and documenting the set of requirements that the software needs to adhere to
- It may include a set of use cases that describe the business needs and user flows that the software must implement

Software requirements can be classified into four broad categories:

1) Functionality
2) External & user interface
3) System features
4) Non-functional

### Design

- Transforming requirements into code
- Breaking down requirements into sets of related components
- Communicating business rules and application logic

### Coding for quality

It refers to characteristics of the code, including attributes:
- Maintainability
- Readability
- Testability
- Security

Quality code must fulfill the intended requirements of the software without defects
- Clean and consistent
- Easy to read and maintain
- Well documented
- Efficient

Coding for quality entails following a set of coding practices during development;
- Following coding standards
- Using linters to detect errors
- Commenting in the code itself to make it easy to understand and modify

### Testing

The process of verifying that the software matches established requirements and is free of bugs
- Identify errors, gaps, or missing requirements
- Ensures reliability, security, performance, and efficiency
- Software testing can often be automated or done manually

The types of testing are;
- Unit testing
- Integration testing
- System testing
- User acceptance testing (UAT) or Beta testing

### Releases

| Alpha                          | Beta               | General Availability |
| ------------------------------ | ------------------ | -------------------- |
| Select stakeholders            | All stakeholders   | Stable               |
| May contain errors             | User testing       | All users            |
| Preview of functioning version | Meets requirements |                      |
| Design changes may occur       |                    |                      | 


### Documenting

**System documentation:**

README files, inline comments, architecture and design documents, verification information, and maintenance guides

**User documentation:**

User guides, instructional videos, manuals, online and inline help

## Requirements

**Steps to gathering requirements:**

- Identifying stakeholders
- Establishing goals and objectives
- Eliciting requirements from the stakeholders
- Documenting the requirements
- Analyzing and confirming the requirements
- Prioritizing

### 1) Identifying stakeholders

**Key personnel:**

- Decision-makers
- End-users
- System administrators
- Engineering Marketing
- Sales
- Customer support

### 2) Establishing goals and objectives

**Goals:** broad, long-term achievable outcomes

**Objectives:** actionable, measurable actions that achieve the goal

### 3) Eliciting, documenting, confirming

**Elicit:**

- Surveys
- Questionnaires
- Interviews

**Document:**

- Align with goals and objectives
- Easily understood

**Confirm:**

- Consistency
- Clarity
- Completeness

### 4) Prioritizing

- Must-have
- Highly desired
- Nice to have

### Requirements documentation:

- Software requirements specification (SRS)
- User requirements specification (URS)
- System requirements specification (SysRS)

**1) Software requirements specification (SRS)**

- Captures functionalities the software should perform
- Establishes benchmarks / service-levels for performance
- Purpose and scope
	- Purpose
		- Who has access to the SRS
		- How it should be used
	- Scope
		- Software benefits
- Constraints, assumptions, dependencies
	- **Constraints:** how the software must operate under given conditions
	- **Assumptions:** required OS or hardware
	- **Dependencies:** on other software products
- Requirements
	- **Functional:** functions of the software
	- **External interface:** users and interactions with other hardware or software
	- **System features:** functions of the system
	- **Non-functional:** performance, safety, security, quality

**2) User requirements specification (URS)**

- Describe business need and end-user expectations
- **User stories:**
	- Who is the user?
	- What is the function that need to be performed?
	- Why does the user want this functionality?
- Confirmed during user acceptance testing
- Often combined into the SRS

**3) System Requirements Specification (SysRS)**

- Outlines requirements of the system
- Broader than an SRS
- Contains;
	- System capabilities
	- Interface and user characteristics
	- Policy
	- Regulation
	- Personnel
	- Performance
	- Security
	- System acceptance criteria
	- Hardware expectations

# The Software Building Process and Associated Roles

## Software Development Methodologies

**Common development methodologies:**

A process is needed to clarify communication and facilitates information sharing among team members.

Some of these methodologies are:
- Waterfall

![](assets/Pasted%20image%2020230520072257.png)

- V-shape model

![](assets/Pasted%20image%2020230520072419.png)

- Agile

![](assets/Pasted%20image%2020230520072609.png)

**Sequential vs. iterative:**

![](assets/Pasted%20image%2020230520072704.png)

### Waterfall pros and cons

![](assets/Pasted%20image%2020230520072759.png)

### V-shape model pros and cons

![](assets/Pasted%20image%2020230520072914.png)

### Agile pros and cons

![](assets/Pasted%20image%2020230520073027.png)

## Software Versions

- Software versions are identified by version numbers indicate:
	- When the software was released
	- When it was updated
	- If any minor changes or fixes were made to the software
- Software developers use versioning to keep track of new software, updates, and patches

**Version numbers:**

- Version numbers can be short or long, with 2, ,3, or 4 set
- Each number set is divided by a period
- An application with a 1.0 version number indicates the first release
- Software with many releases and updates will have a larger number
- Some use dates for versioning, such as Ubuntu Linux version **18.04.2** released in 2018 April, with a change shown in the third number set

**What do version numbers mean?**

Some version numbers follow the semantic numbering system, and have 4 parts separated by a period
- the first number indicates major changes to the software, such as a new release
- The second number indicates that minor changes were made to a piece of software
- The third number in the version number indicates patches or minor bug fixes
- The fourth number indicates build numbers, build dates, and less significant changes

![](assets/Pasted%20image%2020230520074116.png)

**Version compatibility:**

- Older versions may not work as well in newer versions
- Compatibility with old and new versions of software is a common problem
- Troubleshoot compatibility issues by viewing the software version
- Update software to a newer version that is compatible
- Backwards-compatible software functions properly with older versions of files, programs, and systems

## Software Testing

- Integrate quality checks throughout SDLC
- Purpose
	- Ensure software meets requirements
	- Error-free software

**Test cases:**

![](assets/Pasted%20image%2020230520074615.png)

### Three types of testing:

![](assets/Pasted%20image%2020230520074654.png)

1) **Functional testing:**

![](assets/Pasted%20image%2020230520074745.png)

The purpose of functional is to check:
- Usability
- Accessibility

2) **Non-functional testing**

Its attributes are:
- Performance
- Security
- Scalability
- Availability

Non-functional testing questions:
- How does the application behave under stress?
- What happens when many users log in at the same time?
- Are instructions consistent with behavior?
- How does the application behave under different OSs?
- How does the application handle disaster recovery?
- How secure is the application?

3) **Regression Testing**

- Confirms changes don’t break the application
- Occurs after fixes such as change in requirements or when defects are fixed

Choosing test cases for regression testing:

![](assets/Pasted%20image%2020230520075935.png)

### Testing levels

Unit → Integration → System → Acceptance

1) **Unit testing**

- Test a module code
- Occurs during the build phase of the SDLC
- Eliminate errors before integration with other modules

2) **Integration testing**

- Identify errors introduced when two or more modules are combined
- Type of black-box test
- Occurs after modules are combined into larger application

Purpose of integration testing:

![](assets/Pasted%20image%2020230520080401.png)

3) **System testing**

- Compliance with SRS
- Validate the system
- Functional and non-functional
- Staging environment

4) **Acceptance testing**

![](assets/Pasted%20image%2020230520080540.png)

## Software Documentation

- Written assets
- Video assets
- Graphical assets

**Product vs. process documentation:**

| Product Documentation            | Process Documentation            |
| -------------------------------- | -------------------------------- |
| Relates to product functionality | Describes how to complete a task | 

### Types of product documentation

![](assets/Pasted%20image%2020230520080908.png)

1) **Requirements documentation**

Intended for the development team including developers, architects, and QA. Describes expected features and functionality.

It includes:
- SRS
- SysRS
- User acceptance specification

2) **Design documentation**

Written by architects and development team to explain how the software will be built to meet the requirements.
- Consists of both conceptual and technical documents

3) **Technical documentation**

Written in the code to help developers read the code:
- Comments embedded in code and working papers that explain how the code works, documents that record ideas and thoughts during implementation

4) **Quality Assurance documentation**

Pertains to the testing team’s strategy progress, and metrics:
- Test plans, test data, test scenarios, test cases, test strategies, and traceability matrices

5) **User documentation**

Intended for end-users to explain to operate software or help install and troubleshoot system:
- FAQs, installation and help guides, tutorials, and user manuals

### Standard operating procedures

- Accompanies process documentation
- Step-by-step instructions on how to accomplish common yet complex tasks
- Ex: organization specific instructions for check in code to a repository
- Types of SOPs
	- Flowcharts
	- Hierarchical
	- Step-by-step

### Updating documentation

- Must be kept up-to-date
- Documentation should be reviewed and updated periodically

## Roles in Software Engineering Projects

- Project manager / Scrum master

![](assets/Pasted%20image%2020230520082415.png)

- Stakeholders

![](assets/Pasted%20image%2020230520082452.png)

- System / software architect

![](assets/Pasted%20image%2020230520082529.png)

- UX Designer

![](assets/Pasted%20image%2020230520082551.png)

- Developer

![](assets/Pasted%20image%2020230520082627.png)

- Tester / QA engineer

![](assets/Pasted%20image%2020230520082654.png)

- Site reliability / Ops engineer

![](assets/Pasted%20image%2020230520082734.png)

- Product manager / Product owner

![](assets/Pasted%20image%2020230520082805.png)

- Technical writer / Information developer

![](assets/Pasted%20image%2020230520082840.png)
