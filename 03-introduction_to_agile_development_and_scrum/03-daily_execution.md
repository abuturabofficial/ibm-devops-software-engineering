<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Executing the Plan](#executing-the-plan)
  - [Workflow for Daily Plan Execution](#workflow-for-daily-plan-execution)
  - [The Daily Stand-Up](#the-daily-stand-up)
- [Completing the Sprint](#completing-the-sprint)
  - [Using Burndown Charts](#using-burndown-charts)
  - [The Sprint Review](#the-sprint-review)
  - [The Sprint Retrospective](#the-sprint-retrospective)
- [Measuring Success](#measuring-success)
  - [Using Measurements Effectively](#using-measurements-effectively)
  - [Getting Ready for the Next Sprint](#getting-ready-for-the-next-sprint)
  - [Agile Anti-Patterns and Health Check](#agile-anti-patterns-and-health-check)
    - [Scrum health check:](#scrum-health-check)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Executing the Plan

## Workflow for Daily Plan Execution

**Steps in the Scrum Process:**

![](assets/Pasted%20image%2020230519054207.png)

**The Sprint:**

- A sprint is one iteration through the design, code, test, deploy cycle
- It is usually 2 weeks in duration
- Every sprint should have a goal

**Daily Execution:**

- Take the next highest priority item from the sprint backlog
- Assign it to yourself
- Move it in process

![](assets/Pasted%20image%2020230519054352.png)

- No one should have more than one story assigned to them unless they are blocked
- When you are finished, move the story to Review/QA and open a PR
- When the PR is merged, move the story to the Done column

## The Daily Stand-Up

- Occurs every day at the same time and place
- Sometimes called the “daily Scrum”
- Each team member briefly reports on their work
-  Called a “stand-up” during the meeting to keep it short
- Timeboxed to **15 mins**
- Not a project status meeting – all status should be tabled for later discussion

**Daily stand-up meeting:**

Who should attend?
- Scrum master
- Development team
- Product owner (optional)

**Daily stand-up question:**

Each team member answers three questions:
1) What did I accomplish the previous day?
2) What will I work on today?
3) What blockers or impediments are in my way?

**Impediments and blockers:**

- Impediments identified by the team should be unblocked by the scrum master
- Developers that are blocked should work on the next story

**Tabled topics:**

- Topics raised during the daily stand-up should be held until the meeting has ended
- Anyone interested in those topics can stay to discuss

# Completing the Sprint

## Using Burndown Charts

**Milestones and burndowns:**

- Milestones can be created for anything in your project
	- sprint, beta drop, demo, release…
- Burndown charts can be used to measure your progress against a milestone

**Burndown chart:**

- The measurement of story points completed vs. story points remaining for a sprint
- Over time the story points remaining should go down, hence the name: burndown

**Burndown chart examples:**

![](assets/Pasted%20image%2020230519061159.png)

## The Sprint Review

- Live demonstration of implemented stories
- Product owner determines if stories are done based on acceptance criteria
- Done stories are closed

**Sprint Review meeting:**

Who should attend?
- Product owner
- Scrum master
- Development team
- Stakeholders
- Customers (Optional)

**Sprint review:**

- Feedback gets converted into new product backlog stories
- This is where iterative development allows the creation of products that couldn’t have been specified up-front in a plan-driven approach

**Rejected Stories:**

- What about stories that are not considered done?
- Add a label to indicate this and close them
- Write a new story with new acceptance criteria
- This will keep the velocity more accurate

## The Sprint Retrospective

- A meeting to reflect on the sprint
- Measures the health of the process
- The development team must feel comfortable to speak freely

**Who attend the meeting:**

- Scrum master
- Development team

**A time for reflection:**

Three questions are answered:
1) What went well? (keep doing)
2) What didn’t go well? (stop doing)
3) What should we change for the next sprint?

**The goal is improvement:**

- This is critical for maintaining a healthy team
- The scrum master must ensure that changes are made as a result of the feedback
- The goal is to improve for the next sprint

# Measuring Success

## Using Measurements Effectively

**Measurements and metrics:**

- You can’t improve what you can’t measure
- High performing teams use metrics to continually improve
- They take baselines and set goals and measure against them
- Beware of vanity metrics
- Look for the actionable metrics

**Baselines and Goals:**

Baseline:

- It currently requires 5 size team members, 10 hours to deploy a new release of your product
- This costs you $X for every release

Goals:

- Reduce deployment time from 10 hours to 2 hours
- Increase percentage of defects detected in testing from 25% to 50%

**Top 4 actionable metrics:**

1) Mean Lead Time

How long does it take from the idea to production?

2) Release Frequency

How often can you deliver changes?

3) Change Failure Rate

How typically do changes fail?

4) Meantime to Recovery (MTTR)

How quickly can you recover from failure?

**Example metrics:**

- Reduce time-to-market for new features
- Increase overall availability of the product
- Reduce the time it takes to deploy a software release
- Increase the percentage of defects detected in testing before production release
- Provide performance and user feedback to the team in a more timely manner

## Getting Ready for the Next Sprint

**End of sprint activities:**

- Move stories from done to closed
- Close the current milestone
- Create a new sprint milestone
- Adjust unfinished work

**Handling untouched stories:**

- Stories not worked on can be moved to the top of the product backlog
- Resist the urge to move them to the next sprint
- Remember to unassign them from the sprint milestone

**Handling unfinished stories:**

- Don’t move unfinished stories into the next sprint!
- Give the developers credit for the work they did
- This will keep your velocity more accurate
- Adjust the description and story points of the unfinished story, label it unfinished, and move it to done
- Write a new story for the remaining work
- Assign remaining story points and move it to the next sprint

**Ready for the next sprint:**

- All stories assigned to the current sprint are closed
- All unfinished stories are reassigned
- The sprint milestone is closed
- A new sprint milestone is created

## Agile Anti-Patterns and Health Check

**Agile Anti-Patterns:**

- No real product owner/Multiple product owners
- Teams are too large
- Teams are not dedicated
- Teams are too geographically distributed
- Teams are siloed
- Teams are not self-managing

YOU WILL FAIL!

…and you should not wonder why.

### Scrum health check:

- [ ] The accountabilities of product owner, development team(s) and Scrum master are identified and enacted
- [ ] Work is organized in consecutive sprints of 2–4 weeks or fewer
- [ ] There is a sprint backlog with a visualization of remaining work for the sprint
- [ ] At sprint planning a forecast, a sprint backlog, and a sprint goal are created
- [ ] The result of the daily Scrum is work being re-planned for the next day
- [ ] No later than by the end of the sprint, a Done increment is created
- [ ] Stakeholders offer feedback as a result of inspecting the increment at the sprint review
- [ ] Product backlog is updated as a result of the sprint review
- [ ] Product owner, development team(s) and Scrum master align on the work process for their next sprint at the sprint retrospective
