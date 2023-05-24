<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Introduction to Linux Commands](#introduction-to-linux-commands)
  - [Overview of Common Linux Shell Commands](#overview-of-common-linux-shell-commands)
  - [Customizing View of File Content](#customizing-view-of-file-content)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Introduction to Linux Commands

## Overview of Common Linux Shell Commands

**What is a shell?**

- User interface for running commands
- Interactive language
- Scripting language

**Shell command applications:**

- Getting information
	- `whoami` – username
	- `id` – user ID and group ID
	- `unmae` – operating system name
	- `ps` – running processes
	- `top` – resource usage
	- `df` – mounted file systems
	- `man` – reference manual
	- `date` – today’s date
- Navigating and working with files and directories
- Printing file and string contents
- Compression and archiving
	- `tar` – archive a set of files
	- `zip` – compress a set of files
	- `unzip` – extract files from a compressed zip archive
- Performing network operations
	- `hostname` – print hostname
	- `ping` – send packets to URL and print response
	- `ifconfig` – display or configure system network interfaces
	- `curl` – display contents of file at a URL
	- `wget` – download file from a URL
- Monitoring performance and status

## Customizing View of File Content

- `sort` — Sort lines in a file, `-r` will do the same in the reverse
- `uniq` — Filter out repeated lines
- `grep` (“global regular expression print”) — Return lines in file matching pattern
- `grep -i` — makes grep search case-insensitive
- `cut` — Extracts a section from each line
- `paste` — Merge lines from different files
