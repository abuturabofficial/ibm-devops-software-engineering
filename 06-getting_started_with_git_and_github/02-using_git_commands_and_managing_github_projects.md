<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [GitHub Workflows with Branches and Git Commands](#github-workflows-with-branches-and-git-commands)
  - [GitHub Branches](#github-branches)
  - [Cloning and Forking GitHub Projects](#cloning-and-forking-github-projects)
    - [Forking a Project](#forking-a-project)
  - [Managing GitHub Projects](#managing-github-projects)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# GitHub Workflows with Branches and Git Commands

## GitHub Branches

**What are branches?**

- Branches store all files in GitHub
- The master branch stores the deployable code
- Create a new branch for planned changes

![](assets/Pasted%20image%2020230606070241.png)

**Merging Branches:**

- Start with a common base
- The code is branched while new features are developed
- Both branches are undergoing changes
- When the two streams of work are ready to merge, each branch’s code is identified as a tip and the two tips are merged into a third, combined branch

![](assets/Pasted%20image%2020230606070443.png)

**What is a Pull Request?**

- A PR makes the proposed (committed) changes available for others to review and use
- A pull can follow any commits, even if code is unfinished
- PRs can target specific users
- GitHub automatically makes a PR if you make a change on a branch you don’t own
- Log files record the approval of the merge

**Merging into the Master/Main Branch**

- The master branch should be the only deployed code
- Developers can change source files in a branch, but the changes are not released until
	- They are committed
	- A `Pull` command is issued
	- The code is reviewed and approved
	- The approved code is merged back into the master code

## Cloning and Forking GitHub Projects

- Powerful tools include forking and cloning a repository
- Cloning creates a copy of a repository on your local machine
- Cloned copies can sync between locations
- Forking modifies or extends a project

**Remote Repositories:**

- Remote repos are stored elsewhere
- Push, pull, and fetch data to share work
- Origin refers to your fork
- Upstream refers to the original work

### Forking a Project

- Forking
	- Takes a copy of a GitHub repository to use it as the base for a new project
	- Submit changes back to the original repository
- Independently make changes to a project
	- Submit a PR to the original project owner
	- Owner decides whether to accept updates
- Keep a copy of the license file
	- Often a legal requirement
	- Good practice

**Syncing a Fork of a Project:**

To keep a fork in sync with the original work from a local clone:
- Create a local clone of the project
- Configure Git to sync the fork
	- Open terminal and changes to the directory containing the clone
	- To access the remote repository, type `git remote -v`
	- Type `git remote add upstream <clone direcotry>`
	- To see the changes, type `git remote -v`

**Commands for Managing Forks:**

To grab upstream branches
```git
git fetch upstream
```

To merge changes into the master branch
```git
git merge upstream/master
```

## Managing GitHub Projects

**GitHub Developer:**
A Developer communicates with others using these commands:

- `git-clone` from the upstream to prime the local repository
- `git-pull` and `git-fetch` from “origin” to keep-up-to-date with the upstream
- `git-push` to shared repository, if you adopt CVS style shared repository workflow
- `git-format-patch` to prepare email submission
- `git-send-email` to send your email submission without corruption by your MUA
- `git-request-pull` to create a summary of changes for your upstream to pull

**GitHub Integrator:**

An integrator
- Receives changes made by others
- Reviews and responds to PRs
- Publishes the result for others to use

Integrators use the following commands:
- `git-am` to apply patches emailed in from your contributors
- `git-pull` to merge from your trusted lieutenants
- `git-format-patch` to prepare and send suggested alternatives to contributors
- `git-revert` to undo botched commits
- `git-push` to publish the bleeding edge

**GitHub Repository Administrator**

A Repository Administrator sets up and maintains access to the repository by developers
- `git-daemon` to allow anonymous download from repository
- `git-shell` can be used as a restricted login shell for shared central repository users
- `git-http-backend` provides a server-side implementation of Git-over-HTTP (Smart HTTP) allowing both fetch and push services
- `gitweb` provides a web front-end to Git repositories, which can be set-up using the `git-instaweb` script
