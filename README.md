## 2 Weeks Git & Github Challenge

### Here is a _SUMMARY_ of the topics related to git and their _PRIORITY_. 

 CRITICAL                                 |             IMPORTANT                | NICE TO KNOW  |
| :---                                    |               :---:                  |     ---:      |
| DAY 1                                                                                          |
| `What is Git?`                          | `Who uses Git?`                      | `History`     |
|` Difference between git and Github? `   | `What does Git do for us?`           |               |
| DAY 2                                                                                          |
|` Config your Git name and Email `       | `Understanding .git folder`          |               |
|` Terminal `                             |                                      |    |
|` Different ways to interact with git`   |                                      |    |
| DAY 3                                                                               |
|` What is Git Repository `               |                                      |    |
|` git init `                             |                                      |    |
|` git status `                           |                                      |    |
|` The Committing Woorkflow`              |                                      |    |
|` git add`                               |                                      |    |
|` git log `                              |                                      |    |
|` git commit `                           |                                      |    |
| DAY 4                                                                               |
|` .gitignore `                           | ` WRITING Atomic Commits `           | `Working with GUI `|
|                                         | ` Good Commit Messages.  `           | `Amending Commits `|
| DAY 5                                                                               |
|`Branching `                             | ` Navigating Git Dcumentation `      |    |
|` git HEAD `                             |                                      |    |
|` git branch `                           |                                      |    |
|` git switch` or `git checkout`          |                                      |    |








```
DAY 1
```
Learned about "What is Git?" and "What is VCS?".  
>Git is a Version Control System.  
>VCS or Version Control System is a software that tracks and manage changes to files overtime.

Then Took the <b>TERMINAL CRASH COURSE</b>

| Command | Description |
| --- | --- |
| `ls` | list all the content.                                    |
| `open` | The selected directory will open in finder.            |
| `pwd` | Print Working Directory / Current Path.                 |
| `cd` | change directory / it's like double clicking on a file.  |
| `cd ..` | Back one folder.                                      |
| `touch` | creates a file.                                       |  
| `mkdir` |creates a directory.                                   |
| `rm` | remove a fie.(PERMANENTLY).                              |
| `rm -rf` | remove a directory.(PERMANENTLY).                    |
| `ls -a` | shows all files including hidden.                     |

```
DAY 2
```
- What is a "Repository" or "Repo"?       
>It is a workspace and one thing we have to remember that every project should have different repositories.

| Git Command | Description |
| --- | --- |
| `git init` | Creates an empty git repository.                |



- Steps to Use "git init" using terminal:
1. We open "Terminal".
2. Go to a desired position.
3. Make a Directory/Folder by "mkdir".
4. Then use "git init".

:warning: Do Not 'git init' a repository inside a repository.:warning:

If you did make a repository inside a repository itself, then you have to delete the **folder** consisting the second repository.


- COMMITTING
>In Git, commit is the term used for saving changes. Git does not add changes to a commit automatically. You need to indicate which file and changes need to be saved before running the Git commit command. The commit command does not save changes in remote servers, only in the local repository of Git.


```
DAY 3
```

The **"COMMITTING WORKFLOW"** goes like this:
<!-- - First we Make A Folder/File and write some stuff inside it.
- Then we will use `git status` command to see if the folder is alreaady in a repo or not. If not then,
- Then we use the `git init` command to make a `.git` hidden file. (Don't Make a .git file inside a repository).
- Then we will use command  -->
<!-- 
![alt text](https://github.com/raghavguptaa/2Weeks_Git-Github-Challenge/blob/main/Flowchart's/GIT1.png) -->

Example!

![alt text](https://github.com/raghavguptaa/2Weeks_Git-Github-Challenge/blob/main/Flowchart's/GIT2.png)

Basically it's JUST THIS:

![alt text](https://github.com/raghavguptaa/2Weeks_Git-Github-Challenge/blob/main/Flowchart's/GIT3.png)

![alt text](https://github.com/raghavguptaa/2Weeks_Git-Github-Challenge/blob/main/Flowchart's/GIT4.png)

- How to Write Comments on `git commit`
> `git commit -m "<text>" `

[Here is the link how to write best `git commit` messages.](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/)


