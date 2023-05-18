<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Planning to be Agile](#planning-to-be-agile)
  - [Destination Unknown](#destination-unknown)
  - [Agile Roles and the Need for Training](#agile-roles-and-the-need-for-training)
  - [Kanban and Agile Planning Tools](#kanban-and-agile-planning-tools)
- [User Stories](#user-stories)
  - [Creating Good User Stories](#creating-good-user-stories)
  - [Effectively using Story Points](#effectively-using-story-points)
  - [Building the Product Backlog](#building-the-product-backlog)
    - [Sample requirements:](#sample-requirements)
- [The Planning Process](#the-planning-process)
  - [Backlog Refinement: Getting Started](#backlog-refinement-getting-started)
    - [Complete the story template:](#complete-the-story-template)
  - [Backlog Refinement: Finishing Up](#backlog-refinement-finishing-up)
    - [Technical debt](#technical-debt)
    - [Backlog refinement Tips](#backlog-refinement-tips)
  - [Sprint Planning](#sprint-planning)
    - [Sprint planning meeting](#sprint-planning-meeting)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Planning to be Agile

## Destination Unknown

**Deadlines:**

I love deadlines… I like the whooshing sound they make as they fly by.
>— Douglas Adams

- How do you avoid this?

**Plan iteratively:**

- Don’t decide everything at the point when you know the least
- Plan for what you know
- Adjust as you know more
- Your estimates will be more accurate

## Agile Roles and the Need for Training

**Formulas for failure:**

- Product manager becomes product owner
- Project manager becomes scrum master
- Developers (alone) become scrum team

**Product Manager vs. Product Owner:**

![](assets/Pasted%20image%2020230518102246.png)

**Project Manager vs. Scrum Master:**

![](assets/Pasted%20image%2020230518102407.png)

**Development Team vs. Scrum Team:**

![](assets/Pasted%20image%2020230518102459.png)

“Until and unless business leaders accept the idea that they are no longer managing projects with fixed functions, timeframes, and costs, as they did with waterfall, they will struggle to use agile as it was designed to be used.”
>— Bob Kantor, Founder Kantor Consulting Group, Inc.

**The roles have changed:**

- You cannot put people in new roles without the proper training and mindset
- This mindset must come down from upper management

## Kanban and Agile Planning Tools

**Agile planning tools:**

- Tools will not make you Agile
- Tools can support your Agile process
- Many Agile planning tools
- **ZenHub** is one of them

**ZenHub:**

- Plug-in to GitHub
- Provides a kanban board and project management reporting
- Customizable and integrated with GitHub

**Why use ZenHub?**

- Helps you manage where you are in a project based on GitHub Issues
- Provides an easy way to let management know how you are doing
- Maintains up-to-date status due to integration with GitHub
- Allows developers to only use one tool – GitHub

**What is Kanban Board?**

![](assets/Pasted%20image%2020230518103522.png)

**Real World Example:**

![](assets/Pasted%20image%2020230518103603.png)

**Default ZenHub pipelines:**

![](assets/Pasted%20image%2020230518103826.png)

# User Stories

## Creating Good User Stories

**What is a user story?**

A user story represents a small piece of business value that a team can deliver in an iteration.

**Story contents:**

Stories should contain:
- A brief description of the need and business value
- Any assumptions or details
- The definition of “done”

**Story description:**

- User stories document a persona requesting a function to achieve a goal:

As a `<some role>`

I need `<some function>`

So that `<some benefit>`

**Assumptions and details:**

It’s important to document what you know;
- List any assumptions
- Document any details that may help the developer

**Acceptance criteria:**

- It is critical to document the definition of “done”
- I like to use the Gherkin syntax

Given `<some precondition>`

When `<some event happens>`

Then `<some outcome>`

**Sample Story:**

![](assets/Pasted%20image%2020230518111434.png)

**Bill Wake’s INVEST:**

- **I**ndependent
- **N**egotiable
- **V**aluable
- **E**stimable
- **S**mall
- **T**estable

**Epic:**

- A big idea
- A user story that is bigger than a single sprint
- A user story that is too big to estimate on its own

**When to use an epic?**

- When a story is too large in scope it is considered an epic
- Backlog items tend to start as epics when they are lower priority and less defined
- For sprint planning, epics should be broken down into smaller stories

## Effectively using Story Points

**What are story points?**

Story point;
- A metric used to estimate the difficulty of implementing a given user story
- An abstract measure of overall effort

**What does a story point measure?**

![](assets/Pasted%20image%2020230518134656.png)

**Relative T-Shirt sizes**

- Story points acknowledge that humans are bad at estimating time-to-completion
- Instead, story points use relative T-Shirt sizes (S, M, L, XL)
- Most tools use Fibonacci numbers (1, 2, 3, 5, 8, 13, 21)

**Agree on what “medium” means:**

- Since story points are relative, it’s important to agree on what “medium” is
- Then, evaluate from there
- Is it the same, larger, or smaller than medium

**Story size:**

- A story should be small enough to be coded and tested within a single sprint iteration – ideally, just a few days
- Large stories should be broken down into smaller ones

**Story point antipattern**

- Equating a story point to wall-clock time
- Humans are bad at estimating wall-clock time
- Don’t do it!

## Building the Product Backlog

**Steps in the Scrum process:**

![](assets/Pasted%20image%2020230518145409.png)

**Product Backlog:**

- A product backlog contains all the unimplemented stories not yet in a sprint
- Stories are ranked in order of importance and/or business value
- Stories are more detailed at the top, less detailed at the bottom

### Sample requirements:

- What: A service for counting things
- Must allow multiple counters
- Counters must persist across restarts of service
- Counters can be reset

**ZenHub Kanban board:**

![](assets/Pasted%20image%2020230518135923.png)

**Creating new stories**

![](assets/Pasted%20image%2020230518140207.png)

**Story Template:**

**As a** `<some role>`

**I need** `<some function>`

**So that** `<some benefit>`

**Need a service for counting things:**

**As a** User

**I need** a service that has a counter

**So that** I can keep track of how many times something was done

**Creating the next story:**

![](assets/Pasted%20image%2020230518140549.png)

**Must allow multiple counters:**

**As a** User

**I need** to have multiple counters

**So that** I can keep track of several counts at once

**Creating the next story:**

![](assets/Pasted%20image%2020230518140724.png)

**Persist counters across restarts:**

**As a** Service Provider

**I need** the service to persist the last known count

**So that** users don’t lose track of their counts after the service is restarted

**Creating the last story:**

![](assets/Pasted%20image%2020230518140911.png)

**Counters can be reset:**

**As a** System Administrator

**I need** the ability to reset the counter

**So that** I can redo counting from the start

**Stories in the backlog:**

![](assets/Pasted%20image%2020230518141100.png)

**Prioritize the product backlog:**

![](assets/Pasted%20image%2020230518141228.png)

# The Planning Process

## Backlog Refinement: Getting Started

**Backlog refinement:**

- Keep the product backlog ranked by priority so that the important stories are always on the top
- Break large stories down into smaller ones
- Make sure that stories near the top of the backlog are groomed and complete

**Backlog refinement meeting:**

Who should attend?
- Product owner
- Scrum master
- Development team (optional)
	- Lead developer/architect

What is the goal?
- Groom the backlog by ranking the stories in order of importance
- Make sure the story contains enough information for a developer to start working on it

**Backlog refinement workflow:**

![](assets/Pasted%20image%2020230518145923.png)

**New issue triage:**

- Start with new issue triage
- Goal: At the end of backlog refinement, the New Issues column is empty

Take stories from new issues and…
- Move them into the product backlog if they will be worked on soon
- Move them into the icebox if they are a good idea but not now
- Reject them if they are not where you want to go

![](assets/Pasted%20image%2020230518150304.png)

**Backlog refinement workflow:**

- Product owner sorts the product backlog in order of importance
- The team may provide estimates and other technical information
- Large vague items are split and clarified
- The goal is to make the stories “sprint read”

### Complete the story template:

As a `<some role>`

I need `<some function>`

So that `<some benefit>`

**Assumptions and Details:**

`<anything you already know>`

**Acceptance Criteria:**

Given `<some precondition>`

When `<some event>`

Then `<some measurable outcome>`

**Need a service that has a counter:**

![](assets/Pasted%20image%2020230518150901.png)

**Must Persist counter across restarts:**

![](assets/Pasted%20image%2020230518151656.png)

**Deploy service to the cloud:**

![](assets/Pasted%20image%2020230518151911.png)

**Ability to reset the counter:**

![](assets/Pasted%20image%2020230518152926.png)

## Backlog Refinement: Finishing Up

**Label:**

- Help visualize the work

**Labels in GitHub**

![](assets/Pasted%20image%2020230518151322.png)

**Need a service that has a counter:**

![](assets/Pasted%20image%2020230518151518.png)

**Must persist counter across restarts:**

![](assets/Pasted%20image%2020230518151729.png)

**Deploy service to the cloud:**

![](assets/Pasted%20image%2020230518151948.png)

**Ability to reset the counter:**

![](assets/Pasted%20image%2020230518153006.png)



### Technical debt

- Technical debt is anything you need to do that doesn’t involve creating a new feature
- Technical debt builds up when you take shortcuts, but may also occur naturally

**Examples of technical debt:**

- Code refactoring
- Setup and maintenance of environments
- Changing technology like databases
- Updating vulnerable libraries

### Backlog refinement Tips

- You should refine the backlog every sprint to ensure the priorities are correct
- Have at least two sprints’ worth of stories groomed
- The more time you spend refining the backlog, the easier sprint planning will be

## Sprint Planning

- The purpose of sprint planning is to define what can be delivered in the sprint and how that work will be achieved
- This is accomplished by producing a sprint backlog

### Sprint planning meeting

Who should attend?
- Product owner
- Scrum master
- Development team

**Sprint planning goals:**

- Each sprint should have a clearly defined business goal
- The product owner describes the goal and product backlog items supporting it
- It’s important for the whole team to understand why they are building the increment

**Mechanics of sprint planning**

The development team;
- Takes stories from the top of the product backlog and assigns them to the sprint backlog
- Assigns story points and labels
- Ensures each story contains enough information for a developer to start working on it
- Stops adding stories when the team’s velocity is reached

**Team velocity:**

- The number of story points a team can complete in a single sprint
- This will change over time as the team gets better at estimating and better at executing
- The velocity is unique to the team because the story point assignment is unique to the team

**Create a sprint milestone:**

- Create a sprint milestone to start the sprint
- The milestone title should be short
- The description should document the milestone goal
- The duration should be 2 weeks

**Create a milestone:**

![](assets/Pasted%20image%2020230518161219.png)
