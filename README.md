# GitHub Tutorial

### **_By Mishell Torres_**

---
## Git vs. GitHub

**What is Git?**

 Git is a "version control"which keeps the "snapshots"of a code. Git also runs in a command line which
will handles from small to large projects in a effecient speed. Git doesn't require github.

  _Runs in the command line_ 
### Basic Workflow
 You have a directory(folder) or files: 
 
 1. once we initialize git(or version control), we call it a repository 

 2 .edit files (save along the way)
3. add files (to the stage)

 4.commit them with a message

 5.gti push in order to submit your project to the cloud.
   

**What is Github?**

Github stores your code in a cloud and visually track any changes made.Also it could be seen by others
on the website [Github.com](github.com)which is connected to the cloud:

1.store code in the cloud 

2.visually track changes

3.easily collaborate on files

4.Requires Git 


---
## Initial Setup


### What is the SSH Key?
A SSH key stands for Secure Socket Shell is a secures the remotes from the computers,
but if you fork their repository you will be able to clone it and make it yours.
 
### What is git config?
Git config is when you are configuring you username and email in order to connect it to github.
You can specify Git configuration settings with the `git config` command.
One of the first things you did was set up your name and email address when making your first repository
you need use::
    `git config --global user.name “First Last”`
    `git config --global user.email “username@hstat.org”`
  After using git config you would be able to connect it to github.
  
  
---
## Repository Setup
When making a new repository you need to go to [github](github.com) then:

1.At the top right corner there is a  **+** 

2.Click New repository.

3.Then type a name for your repository

4.Click "Create repository".

 And then you could go back to [cloud 9](c9.io)then you could do `git add`in order to add your file to github 
then commited with a short and specific message. Then do `git push` for the file to go up to the cloud(github)

---
## Workflow & Commands


1._git init_ // initializes git in our directory called a repository for version control

2._git status_ // is use to check were you at and also to see what you are missing or to check what you did
in order to get to that place.(it will be red if you are missing a step)


3._git add file.ext_ // add the file(s) to the stage (for example:"README.md" to be committed, after you do `git status`

4._git status_ // after doing step 3 you do `git status` because you have to check if your file has been added
(then the files name would  be green)

5._git commit -m "short and specific message"_//git commit takes a snapshots of the file by adding a short and specific message.

6._git push_ // after going`git commit` you do `git push` because you are sending your commits from your local repo 
into your remote repo (up to the cloud: Github)

7._git pull_//would pull or bring down any changes that someone made,from the remote repository down to your local repository

 
---
## Error handling

When having a error you don't have to panic because there are ways to solve your problems.One of the problems that 
we have as using c9.io is that sometimes we just put `git init` in a wrong repository.So what `git init`does is that
it create an empty Git repository or reinitialize an existing one .

###Removing
 
 When moving a repository you have to use `rm -rf`then the name of the repository.







