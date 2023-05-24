<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Introduction to Shell Scripting](#introduction-to-shell-scripting)
  - [Shell Scripting Basics](#shell-scripting-basics)
  - [Filters, Pipes, and Variables](#filters-pipes-and-variables)
    - [Pipes and filters:](#pipes-and-filters)
    - [Shell variables:](#shell-variables)
    - [Environment Variables:](#environment-variables)
  - [Useful Features of the Bash Shell](#useful-features-of-the-bash-shell)
    - [Metacharacters](#metacharacters)
    - [Quoting](#quoting)
    - [I/O redirection](#io-redirection)
    - [Command substitution](#command-substitution)
    - [Command line arguments](#command-line-arguments)
    - [Batch vs. concurrent modes](#batch-vs-concurrent-modes)
  - [Scheduling Jobs using Cron](#scheduling-jobs-using-cron)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Introduction to Shell Scripting

## Shell Scripting Basics

**What is  a script?**

- **Script:** list of commands interpreted by a scripting language
- Commands can be entered interactively or listed in a text file
- Scripting languages are interpreted at runtime
- Scripting is slower to run, but faster to develop

**What is a script used for?**

- Widely used to automate processes
- ETL jobs, file backups and archiving, system admin
- Used for application integration, plug-in development, web apps, and many other tasks

**Shell scripts and the ‘shebang’**

- Shell script – executable text file with an interpreter directive
- Aka ‘shebang’ directive

```bash
#!interpreter [optional-arg]
```

- ‘interpreter’ – path to an executable program
- ‘optional-arg’ – single argument string

**Exampel – ‘shebang’ directives**

Shell script directive:

```sh
#!/bin/sh
#!/bin/bash
```

Python script directive:

```python
#!/usr/bin/env python3
```

## Filters, Pipes, and Variables

### Pipes and filters:

Filters are shell commands, which:
- Take input from standard input
- Send output to standard output
- Transform input data into output data
- Examples are `wc, cat, more, head, sort`, …
- Filters can be chained together

Pipe command – `|`
- For chaining filter commands

```bash
commmand1 | command2
```

- Output of command 1 is input of command 2
- Pipe stands for pipeline

### Shell variables:

- Scope limited to shell
- `Set` – list all shell variables

**Defining shell variables:**

```bash
var_name=value
```

- No spaces around `=`

```bash
unset var_name
```

- deletes `var_name`

### Environment Variables:

- Extended scope

```bash
export var_name
```

- `env` — list all environment variables

## Useful Features of the Bash Shell

### Metacharacters

- `#` — precedes a comment
- `;` — command separator
- `*` — filename expansion wildcard
- `?` — single character wildcard in filename expansion

![](assets/Pasted%20image%2020230524080425.png)

### Quoting

- `\` — escape special character interpretation
- `""` — interpret literally, but evaluate meta-characters
- `''` — interpret literally

![](assets/Pasted%20image%2020230524080609.png)

### I/O redirection

Input/Output, or I/O redirection, refers to a set of features used for redirecting
- `>` — Redirect output to file
- `>>` — Append output to a file
- `2>` — Redirect standard error to a file
- `2>>` — Append standard error to a file
- `<` — Redirect file contents to standard input

![](assets/Pasted%20image%2020230524080924.png)

### Command substitution

- Replace command with its output

```bash
$(command) or `command`
```

- Store output of `pwd` command in `here`:

![](assets/Pasted%20image%2020230524081201.png)

### Command line arguments

- Program arguments specified on the command line
- A way to pass arguments to a shell script

```bash
./MyBashScript.sh arg1 arg2
```

### Batch vs. concurrent modes

Bath mode:
- Commands run sequentially

```bash
command1; command2
```

Concurrent mode:
- Commands run in parallel

```bash
command1 & command2
```

## Scheduling Jobs using Cron

**Job scheduling**

- Schedule jobs to run automatically at certain times
	- Load script at midnight every night
	- Backup script to run every Sunday at 2 AM
- Cron allows you to automate such tasks

**What are cron, crond, and crontab?**

- Cron is a service that runs jobs
- Crond interprets ‘crontab files’ and submits jobs to cron
- A crontab is a table of jobs and schedule data
- Crontab command invokes text editor to edit a crontab file

**Scheduling cron jobs with crontab**

![](assets/Pasted%20image%2020230524082230.png)

**Viewing and Removing cron jobs**

![](assets/Pasted%20image%2020230524082411.png)
