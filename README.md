## 2 Weeks Git & Github Challenge

### Here is a _SUMMARY_ of the topics related to git and their _PRIORITY_. 

 CRITICAL                                 |             IMPORTANT                | NICE TO KNOW  |
| :---                                    |               :---:                  |     ---:      |
| DAY 1                                                                                          |
| `What is Git?`                          | `Who uses Git?`                      | `History`     |
|` Difference between git and Github? `   | `What does Git do for us?`           |               |
| DAY 2                                                                                          |
|` Config your Git name and Email `       | `Understanding .git folder`          |               |
|` Terminal Crash Course `                |                                      |    |
|` Different ways to interact with git`   |                                      |    |
| DAY 3                                                                               |
|` What is Git Repository `               |                                      |    |
|` git init `                             |                                      |    |
|` git status `                           |                                      |    |
|` git add`                               |                                      |    |
|` git log `                              |                                      |    |
|` git commit `                           |                                      |    |
|` The Committing Workflow`               |                                      |    |
| DAY 4                                                                               |
|` .gitignore `                           | ` WRITING Atomic Commits `           | `Working with GUI `|
|                                         | ` Good Commit Messages.  `           | `Amending Commits `|
| DAY 5                                                                               |
|`Branching `                             | ` Navigating Git Documentation `     |    |
|`git HEAD `                              |                                      |    |
|`git branch `                            |                                      |    |
|`git switch` or `git checkout`           |                                      |    |
| DAY 6                                                                               |
|`Fast Forward Merges `                   |                                      |`Using VS CODE to Resolve Conflict`|
|`git merge `                             |                                      |    | 
|`Resolving Merge Conflict`               |                                      |    | 
| DAY 7                                                                               |
|`Reading Diffs `                         | ` Diff Branches `                    |    |
|` git diff `                             | ` Diffing Commets`                   |    |
|                                         | ` Diffing Specific Files`            |    |
|                                         | ` Git diff --staged`                 |    |
 








```
DAY 1
```



- "What is Git?" and "What is VCS?".  
>Git is a Version Control System.  
>VCS or Version Control System is a software that tracks and manage changes to files overtime.
>Which changes were made?
>Who made the changes?
>When were the changes made?
>Why were changes needed?

- Difference Between Git and Github.

| Git           | Github        |
| ------------- | ------------- |
| Git is a software.  | GitHub is a service.  |
| Git is a command-line tool  | GitHub is a graphical user interface  |
| Git is installed locally on the system  | GitHub is hosted on the web |
| Git is focused on version control and code sharing.| GitHub is focused on centralized source code hosting.  |
| Git has no user management feature.  | GitHub has built-in user management feature  |


- [Who uses Git?](https://stackshare.io/git#:~:text=Who%20uses%20Git%3F&text=7047%20companies%20reportedly%20use%20Git,Netflix%2C%20Shopify%2C%20and%20Udemy.)
- [What does Git Do for us?](https://medium.com/swlh/git-as-the-newbies-learning-steroid-963a2146220b)
- [Histroy of GIT.](https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git)

 




```
DAY 2
```




- Configure your Git name and Email.
> 1. Open the command line.
> 2. Set your username: git config --global user.name "FIRST_NAME LAST_NAME"
> 3. Set your email address: git config --global user.email "MY_NAME@example.com"


<b>TERMINAL CRASH COURSE</b>

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

- Different ways to interact with git.
> There are Two ways, one is the command line and the other is with use of different applications like GitKraken, Github Desktop, etc.


- Understanding the .git Folder.
> The . git folder contains all the information that is necessary for your project in version control and all the information about commits, remote repository address, etc. All of them are present in this folder. It also contains a log that stores your commit history so that you can roll back to history.




```
DAY 3
```




- What is a "Repository" or "Repo"? For Detail go to [this](https://www.geeksforgeeks.org/what-is-a-git-repository/) link.
>Repositories in GIT contain a collection of files of various different versions of a Project. These files are imported from the repository into the local server of the user for further updations and modifications in the content of the file.


| Git Command | Description |
| --- | --- |
| `git init` | initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.   |
| `git status` | shows the status of changes as untracked, modified, or staged. |
| `git add`    | This command performs staging, the second part of that three-step process. Any changes that are staged will become a part of the next snapshot and a part of the project’s history. |
| `git log`    | The git log command shows a list of all the commits made to a repository. You can see the hash of each Git commit, the message associated with each commit, and more metadata. |
| `git commit` | saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.  |

- Steps to Use "git init" using terminal:
1. We open "Terminal".
2. Go to a desired position.
3. Make a Directory/Folder by "mkdir".
4. Then use "git init".

:warning: Do Not 'git init' a repository inside a repository.:warning:

If you did make a repository inside a repository itself, then you have to delete the **folder** consisting the second repository.



- The **"COMMITTING WORKFLOW"** goes like this:
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






```
DAY 4
```



- .What are gitignore files?
> Specifies intentionally untracked files to ignore.
> Example: There are projects where you use some API's like Stripe or Paypal for user transactions and you don't want to put the authentic key to github. So we put the file name in .gitignore folder. 
> There is a website which gives us all the .gitignore file names accoording to our project. You can find it [HERE](https://www.toptal.com/developers/gitignore)


- Writing Atomic Commits.
> An atomic commit is a commit that is focused on one context and one context only. For more info go [HERE](https://coderwall.com/p/jmqp0a/why-and-how-i-craft-atomic-commits-in-git)


- How to Write Comments on `git commit`
> `git commit -m "<text>" `

[Here is the link how to write best git commit messages.](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/)


- Working with GUI
> You will find an answer [HERE](https://git-scm.com/book/en/v2/Appendix-A%3A-Git-in-Other-Environments-Graphical-Interfaces)


- Ammending Commits.

| Git Command | Description |
| --- | --- |
| `git commit --amend` | This command is a convenient way to modify the most recent commit. It lets you combine staged changes with the previous commit instead of creating an entirely new commit. It can also be used to simply edit the previous commit message without changing its snapshot.  |




```
DAY 5
```


- Branching
> A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master . As you start making commits, you're given a master branch that points to the last commit you made. Every time you commit, the master branch pointer moves forward automatically.
> If we make changes oon one branch, they do not impact other branches. (Unless we merge the changes).

- MASTER branch
> In Git, "master" is a naming convention for a branch. After cloning (downloading) a project from a remote server, the resulting local repository has a single local branch: the so-called "master" branch. This means that "master" can be seen as a repository's `"default"` branch.

| Git           | Github        |
| ------------- | ------------- |
| Master is Default.       | Main is Default.   |

- What is "HEAD" in git?
> When working with Git, only one branch can be checked out at a time - and this is what's called the "HEAD" branch. Often, this is also referred to as the "active" or "current" branch.
> Git makes note of this current branch in a file located inside the Git repository, in .git/HEAD. (This is an internal file, so it should not be manually manipulated!)

| Git Command | Description |
| --- | --- |
| `git branch` | This command is to view your existing branches. |
> Active / Selected Branch will have a <b> "*" </b> in front of name.
![alt](https://github.com/raghavguptaa/2Weeks_Git-Github-Challenge/blob/main/Images/Git_Branch.png)


| Git Command | Description |
| --- | --- |
| `git switch` or `git checkout` | The "switch" command allows you to switch your current HEAD branch. It's relatively new (added in Git v2.23) and provides a simpler alternative to the classic "checkout" command. For [MORE](https://www.git-tower.com/learn/git/commands/git-switch/). |
