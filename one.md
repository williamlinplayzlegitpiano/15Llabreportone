# CSE 15L: Basic Filesystem Commands
## William Lin, 01/11/2024
---

Welcome! In this blog post, we will be discussing the basic filesystem commands `cd`, `ls`, and `cat`. Each command will be shown in situations where there are no arguments, a path to a directory as an argument, and a path to a file as an argument

---
## `cd` Command

**Purpose: to change directory**

>Example 1: Using the command with no arguments

Command: `cd`

Scenario 1:

![image](https://github.com/williamlinplayzlegitpiano/15Llabreportone/assets/55766910/9bb6dd87-4dfd-48a2-bdca-39b20bd065bf)

Working Directory: `/home`

Explanation: `cd` with no arguments can have different results given its current working directory. If the current working directory is `/home`, it will change from `/home` to `/home` in the command prompt, essentially not changing the command prompt. `cd` does not have output.

Scenario 2:

![image](https://github.com/williamlinplayzlegitpiano/15Llabreportone/assets/55766910/8b8fabf1-2e38-4e3e-b3b0-391b99e8da78)

Working Directory: `/salutations`

Explanation: If the current working directory is a repository or file, `cd` will change the current working directory to `/home` in the command prompt. `cd` does not have output.

>Example 2: Using the command with a path to a *directory* as an argument

Command: `cd (directory name)`

![image](https://github.com/williamlinplayzlegitpiano/15Llabreportone/assets/55766910/46f739f7-c93d-4a25-9170-6d467306129e)

Working Directory: `/home/salutations`

Explanation: `cd salutations` changes the working directory from `/home` to a new location, `/home/salutations`. This change is shown in the prompt, where it says `[user@sahara ~/salutations]$` instead of `[user@sahara ~]$`.

>Example 3: Using the command with a path to a *file* as an argument

Command: `cd (file name)`

![image](https://github.com/williamlinplayzlegitpiano/15Llabreportone/assets/55766910/015304d4-8462-43cf-8ada-08261e9e6ae0)

Working Directory: none

Explanation: Error. `cd` command is used for changing directory. A file is not a directory, hence showing the the output `bash: cd: hello!.txt: Not a directory`.

---
## `ls` Command

>Example 1: Using the command with no arguments

Command: `ls`

![image](https://github.com/williamlinplayzlegitpiano/15Llabreportone/assets/55766910/8ada7fe7-9957-4cd7-afbe-e49ea8b6a3e8)

Working Directory: `/home`

Explanation: `ls` shows the names of files and folders inside the current directory. In the current working directory, we have one folder: salutations. 

>Example 2: Using the command with a path to a *directory* as an argument

Command: `ls (directory name)` 

![image](https://github.com/williamlinplayzlegitpiano/15Llabreportone/assets/55766910/20ebc3e2-1c90-45e2-b159-4603db61c2e1)

Working Directory: `/home/salutations`

Explanation: `ls (directory name)` shows the names of files and folders inside the specified directory. In the the directory `salutations`, we have two files: `bonjour!.txt` and `hello!.txt`



  


