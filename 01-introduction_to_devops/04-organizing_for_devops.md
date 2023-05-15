<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Organizational Impact of DevOps](#organizational-impact-of-devops)
  - [Organizational Impact of DevOps](#organizational-impact-of-devops-1)
  - [There is No DevOps Team](#there-is-no-devops-team)
  - [Everyone is Responsible for Success](#everyone-is-responsible-for-success)
- [Measuring DevOps](#measuring-devops)
  - [Rewarding for “A” while hoping for “B”](#rewarding-for-a-while-hoping-for-b)
  - [Vanity metrics vs. actionable metrics](#vanity-metrics-vs-actionable-metrics)
  - [How to Measure Your Culture](#how-to-measure-your-culture)
  - [Comparison of DevOps to Site Reliability Engineering](#comparison-of-devops-to-site-reliability-engineering)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Organizational Impact of DevOps

## Organizational Impact of DevOps

**How does organization affect DevOps?**

Is the culture of your organization agile?
- Small teams
- Dedicated teams
- Cross-functional teams
- Self-organizing teams

**Conway’s Law:**

> “Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization’s communication structure.” — Melvin Conway, Datamation, 1968

**Traditional organization around technology:**

![](assets/Pasted%20image%2020230515090250.png)

**Organized around business domains:**

![](assets/Pasted%20image%2020230515090358.png)

**Align teams with the business:**

- Each team has its own mission aligned with the business
- Teams have end-to-end responsibility for what they build
- Teams should have a long-term mission, usually around a single business domain

## There is No DevOps Team

**DevOps is often misunderstood:**

- Dev and Ops are not separate things
- You aren’t a DevOps if you’re not a Dev, and other way is also true

**Perspectives on DevOps:**

![](assets/Pasted%20image%2020230515092132.png)

**DevOps is not a team:**

>“The DevOps movement addresses the dysfunction that results from organizations composed of functional silos. Thus, creating another functional silo that sits between Dev and Ops is clearly a poor (and ironic) way to try, and solve these problems.” — Jez Humble, The DevOps Handbook

**Working in silos doesn’t work:**

![](assets/Pasted%20image%2020230515092536.png)

**A DevOps team means we’re DevOps, right?**

![](assets/Pasted%20image%2020230515092628.png)

**DevOps is not a job title:**

- A culture transformation on an organizational scale
- Development and operations engineers working together
- Following lean and agile principles
- Cross-functional teams with openness, transparency, and trust as pillars

## Everyone is Responsible for Success

**Bad behavior:**

>“Bad behavior arises when you abstract people from the consequences of their actions.” — Jez Humble, Continuous Delivery

**Functional silos breed bad behavior:**

![](assets/Pasted%20image%2020230515093533.png)

**Actions have consequences:**

- Make people **aware** of the consequences of their actions
- Make people **responsible** for the consequences of their actions

**DevOps organizational objective:**

Shared consciousness

…with

distributed (local) control

# Measuring DevOps

## Rewarding for “A” while hoping for “B”

**On the folly of rewarding for A, while hoping for B**

>“Whether dealing with monkeys, rats, or human beings, it is hardly controversial to state that most organisms seek information concerning what activities are rewarded, and then seek to do (or at least pretend to do) those things, often to the virtual exclusion of activities not rewarded. The extent to which this occurs, of course, will depend on the perceived attractiveness of the rewards offered, but neither operant nor expectancy theorists would quarrel with the essence of this notion.” — Steven Kerr, The Ohio State University

**Measure what matters:**

![](assets/Pasted%20image%2020230515095748.png)

**Social metrics:**

- Who is leveraging the code you are building?
- Whose code are you leveraging?

**DevOps metrics:**

- A baseline provides a concrete number for comparison as you implement your DevOps changes
- Metric goals allow you to reason about these numbers and judge the success of your progress

**DevOps changes the objective:**

- Old school is focused on **mean time to failure** (MTTF)
- DevOps is focused on **mean time to recovery** (MTTR)

## Vanity metrics vs. actionable metrics

**Vanity metrics:**

- We had 10,000 daily hits to our website!
- Now what? (What does a hit represent?)
- What actions drove those visitors to you?
- Which actions to take next?

**Actionable metrics:**

![](assets/Pasted%20image%2020230515100442.png)

**Actionable metric examples:**

- Reduce time to market
- Increase overall availability
- Reduce time to deploy
- Defects detected before production
- More efficient use of infrastructure
- Quicker performance feedback

**Top four actionable metrics:**

1) Mean lead time
2) Release frequency
3) Change failure rate
4) Mean time to recovery (MTTR)

## How to Measure Your Culture

**Culture measurements:**

You can rate statements developed by Dr. Nicole Forsgren to measure your team’s culture, including statements about information, failures, collaboration, and new ideas.

![](assets/Pasted%20image%2020230515101705.png)

**Strongly agree or disagree?**

- On my team, information is actively sought
- On my team, failures are learning opportunities and messengers of them are not punished
- On my team, responsibilities are shared
- On my team, cross-functional collaboration is encouraged and rewarded
- On my team, failure causes inquiry
- On my team, new ideas are welcomed

## Comparison of DevOps to Site Reliability Engineering

**What is SRE?**

>“…what happens when a software engineer is tasked with what used to be called operations.” —Ben Treynor Sloss

Goal: Automate yourself out of a job.

**Tenets of SRE:**

- Hire only software engineers
- Site reliability engineers work on reducing toil through automation
- SRE teams are separate from development teams
- Stability is controlled through error budgets
- Developers rotate through operations

**Team differences:**

- SRE maintains separate development and operations silos with one staffing pool
- DevOps breaks down the silos into one team with one business objective

**Maintaining stability:**

![](assets/Pasted%20image%2020230515102658.png)

**Commonality:**

- Both seek to make both Dev and Ops work visible to each other
- Both require a blameless culture
- The objective of both is to deploy software faster with stability

**DevOps + SRE:**

- SRE maintains the infrastructure
- DevOps uses infrastructure to maintain their applications

![](assets/Pasted%20image%2020230515102924.png)
