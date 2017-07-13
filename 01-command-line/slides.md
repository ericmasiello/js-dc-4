

<img src="https://ga-core.s3.amazonaws.com/production/uploads/program/default_image/5225/JS-logo-official.png" style="max-width: 100px; border: none; box-shadow: none" />
## Class 01: The Command Line

---

### Agenda

| Timing | Topic                                    |
| ------ | ---------------------------------------- |
| 5  min | Check In                                 |
| 40 min | Introducing the Terminal                 |
| 20 min | Activity: Scavenger Hunt                 |
| 10 min | Break                                    |
| 60 min | Git and GitHub                           |
| 10 min | Break                                    |
| 50 min | Git and GitHub (cont'd)                  |
| 10 min | Closing                                  |
| 5  min | Check Out                                |

---
### Learning Goals
* Navigate using the terminal
* Manage a local repository in Git
* Fork a repository
* Clone a repository
* Make a pull request on a repository

---
## The Terminal

--
### What is the Terminal?
- tool for navigating the file system on our computer

Note:
- Terminal = Command Line = Console
- Terminal is a tool for us to navigate the file system on our computer
- Predates the GUI (i.e. Finder on a Mac or Explorer on a PC)
- Character User Interface

--
### Why use it?
1. Concise and powerful
2. Efficient
3. Requires fewer resources
4. Expert-friendly
5. Easy to automate via scripting

Note:
1. It's concise and powerful - you can do a lot with relatively few keystrokes,
2. It's efficient - both as a use of time and for your machine, because it requires fewer resources,
3. It's expert-friendly - which is to say that if you invest a little time in getting good at using the command line, the productivity benefits that you'll reap are incredible,
4. It's easy to automate via scripting - you can write scripts that will handle repetitive tasks.

--

### Running Terminal

#### Mac:
- Open the "Terminal" app (Applications > Utilities > Terminal)

#### Windows:
- Open the "Git BASH" application

--
### Anatomy of the Terminal

<img src="../assets/00-command-line-01.png" style="max-width: 600px; border: none;box-shadow: 0px 18px 20px 6px rgba(0,0,0,0.2);" />

--
#### The Terminal

<img src="../assets/00-command-line-02.png" style="max-width: 600px; border: none;box-shadow: 0px 18px 20px 6px rgba(0,0,0,0.2);" />

--
#### The Terminal

<img src="../assets/00-command-line-03.png" style="max-width: 600px; border: none;box-shadow: 0px 18px 20px 6px rgba(0,0,0,0.2);" />

--
#### The Terminal

<img src="../assets/00-command-line-04.png" style="max-width: 600px; border: none;box-shadow: 0px 18px 20px 6px rgba(0,0,0,0.2);" />

--
#### The Terminal

<img src="../assets/00-command-line-05.png" style="max-width: 600px; border: none;box-shadow: 0px 18px 20px 6px rgba(0,0,0,0.2);" />

--
#### The Terminal

<img src="../assets/00-command-line-06.png" style="max-width: 600px; border: none;box-shadow: 0px 18px 20px 6px rgba(0,0,0,0.2);" />

--
#### The Terminal

<img src="../assets/00-command-line-07.png" style="max-width: 600px; border: none;box-shadow: 0px 18px 20px 6px rgba(0,0,0,0.2);" />

--
### Terminal Anatomy

| Part        | Description                       |
| ----------- | --------------------------------- |
| Prompt      | Where you enter commands          |
| Command     | Text to be executed               |
| Input       | Options and Data for the command  |
| Flag/Option | Specific data for a given command |
| Output      | What the command returns          |

--
### Code Along!
Open your Terminal and follow along

Note:
### Navigating our File System
- start by figuring out where we are now:
  - print working directory - `pwd`
  - *absolute path*
  - *root dir `~/`*
- now we know where we are, lets go somewhere. Where can we go from here?
  - list contents - `ls`
  - list all directories in the current folder
  - what's a directory?
- check pace
- lets open one of these folders
  - change directories - `cd`
  - change to (a) a specific folder, (b) go up a folder, (c) go up more than one folder, (d) go to the home folder
- navigating folders is super useful, but you guys probably don't have that many yet - so lets make some
  - make directory - `mkdir`

--
### Unstructured Review
- practice navigating around your computer using the command line
- try each command at least 5 times

Note:
- `pwd`
- `cd`
- `ls`
- `mkdir`

--
### Navigating the Command Line

| Command       | Description                                |
| -----------   | ------------------------------------------ |
| **`pwd`**     | **P**rint **w**orking **d**irectory        |
| **`ls`**      | **L**i**s**t the contents of the directory |
| **`cd`**      | **C**hange **d**irectories                 |
| `cd myFolder` | go into myFolder                           |
| `cd ../`      | go up one folder/directory                 |
| `cd ..`       | shorthand for `cd ../`                     |

--
### Paths and Directories

| Path     | Description        |
| -------- | -----------------  |
| `./`     | current directory  |
| `../`    | up one directory   |
| `../../` | up two directories |
| `/`      | root directory     |
| `~/`     | 'home' directory   |

--
### Working with Files and Folders
| Command     | Description                                |
| ----------- | ------------------------------------------ |
| `mkdir`     | **M**a**k**e **dir**ectory                 |
| `rmdir`     | **R**e**m**ove empty **dir**ectories       |
| `rm`        | **R**e**m**ove files or directories        |
| `mv`        | **m**o**v**e file or directory             |
| `cp`        | **c**o**p**y file or directory             |
| `touch`     | Create an empty file                       |
| `echo`      | Return a string                            |

--
## Break

---
## Terminal Review

--
### Terminal Review
- Count off 1-4 and find a corner of the room
- A question or command will come up on the board
- Go around your group answering the question or explaining what the command does

--
### `pwd`

--
### How to I create a folder through the command line?

--
### `rmdir test-directory`

--
### `touch test.js`

--
### `rm test.js`

--
### `cp -r test-directory test-directory2`

--
### `cp test-directory/* test-directory2/`

--
### `rm -rf test-directory`

--
### `mv test-directory/* test-directory2/`

--
### What is a relative path?

--
### What is an absolute path?

--
## Done!
Great job!

---
## Git and GitHub

--
### Overview
- Git: Version Control System
- GitHub: Saas tool for working with Git

Note:
- Git:
  - A version control system
  - not so different from track changes in Microsoft word, but a lot more powerful
  - the goal of a version control system is to allow multiple people to work on the same code base easily, keeping track of everyone's changes and the history of all those changes
- Github
  - Saas platform for working with git

--
### Version Control System

--
### Git Overview
- Creating and working with a repository
- Forking a repository
- Cloning a repository

--
### 20,000 Feet
What is Version Control and how does it work?

--
### Key terms

| Term  | Definition |
| ----- | ---------- |
| repository | Folder where git manages changes and history |
| local | the version of the repository on your machine |
| remote/origin | a shared version of the repository hosted on a server |
| fork | a snapshot or copy of a repository |
| pull request | submitting changes from a fork to be merged |
| upstream | The original repository of a forked repository |

--
### Code Along!

Note:
- create a new repository using git init
- add a file to a repository
- commit those changes
- create a new repository on GitHub
- push your changes to Github

--
## Git Commands
| Command                     | Description                               |
| --------------------------- | ----------------------------------------- |
| `git init`                  | Initializes a new repository              |
| `git add`                   | Stages a set of files to be committed     |
| `git add .`                 | Stages all modified files                 |
| `git add myFile.js`         | Stages a specific file                    |
| `git commit -m "my commit"` | Commits staged files to the repository    |
| `git push origin master`    | Pushes commits to master branch of origin |

-- 

### Code Along Part 2:
#### Forking, Cloning, Pull Requesting

Note:
### Forking a Repository
- pair up wit the person sitting next to you
- have them slack you the link to their repository and slack them the link to yours
- Once you've opened the repository in github

### Cloning a Repository
- Copy the link for the repository
- in the command line, clone the repository to a new directory

### Making a Pull Request
- push your changes to origin of the forked repository
- go to the github.com for the forked repository and navigate back to the original repository
- click on 'Pull Request', then 'New' to create a pull request. Give it a title and then write a message describing the changes you made.
- Go back to your own repository and check the pull request. Go ahead and merge it in

### Working with upstream
- pull down the changes your partner made using `git pull`
- make a change to `index.js` and push it up to your origin
- now switch to your clone of your partner's repository
- navigate to the github.com page for your partners repo and copy the link
- switching back to the command line, add the repository as upstream by running `git remote add upstream https://github.com/username/repository`
- now run `git pull upstream master` to synchronize their changes with yours, and push them to your remote origin.


---
## Scavenger Hunt

--
### Scavenger Hunt
- **Copy** at least 5 rubies into your stash
- Can't include any trees!

Note:
- have student create a top level directory called "stash"
- have student traverse the project and use `cp` to copy different rubies into their stash directory

https://github.com/ga-students/js_dc_scavenger_hunt/blob/master/readme.md
