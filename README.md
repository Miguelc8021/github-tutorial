# GitHub Tutorial

by : Miguel Crisantos

---
### _Git_ vs. **GitHub**

**Main difference:** _Git_ DOES NOT require **Github**

_What is Git?_

_Git_ is a command line based system which can be used **offline**.  It is more for personal use which doesn't allow for much collaboration.  Users can efficently make and track changes 

_What is Github?_

**Github** is a cloud based system (**online**) where you are able to store your projects, so that people around the world are able to see & take your work then out their own spin on it. Git allows for a lot of **collaboration**.

---
## Initial Setup

The first & **MAIN** step for setting uo your Ide is to create a Github account.  You will need a username & password that will be easy to memorize, please don't forget your account details, we will use them later on.

For a better understanding on how to set up your Ide please click [this link](https://github.com/hstatsep/ide50)

We have two different options when we sept up our Ide, these options are Https & SSH. Let's completely ignore Https for now, let's focus on SSH since it's more important to us at the moment. SSH is important because it is makes things much faster & easier to do. Through SSH we don't have to enter our account details when we want to connect our Ide & Github.

---
## Repository Setup

Repositories are made on Git, so what we want to do is...
1. Choose the directory that you would like to make a respository in 
2. You want to type in the command 'git init', which initializes git
3. Now you want to make a file using the command `touch (filename)`
4. Now we want to add some text into our file, so we must use to command `c9 (filename)`
5. Once we have added text, we must add it. Let's use the command `git add `
6. We're ready to commit these changes, Use the command `git commit -m "commit message" `
7. Finally let's use the command `git push`.


Repositories are presented on Github, so what we want to do is..
1. Go to Github.com & log in with the account you have made earlier 
2. In the far right of our screen we'll see a "+" symbol, click on that & click on the "New Repository" option.
3. We must give our Github repository the same name as the repository on our Ide.
4. Once our repository is made, we should copy the SSH.
5. Once the SSH is copied, we can paste it into our Ide.
6. Now we are able to push our lines of code to Github.


---
## Workflow & Commands

The workflow order of Git is...
1. Make changes to your text file
2. `git status`
3. `git add .`
4. `git commit -m "commit message" `
5. `git push`
6. **REPEAT**

---
## Rolling Back Changes

Rolling back changes are a number of commands that you can do just in case you make a mistake.

Let's say you have make a commit in the early stages of your project, a number of commits later you realize that you have made a big silly mistake.  You don't want to start over or delete everything you have written.

Use can simply use `git revert SHA`

When you use this command you should first type the command `git log` to see the commits you have made. You will see a set of number & letters, now based on the commit you want to revisit, copy it's certain number & letters. By doing this, the changes of a certain commit will be brought back and all the new commits will be delete.

