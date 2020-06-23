# Git/Github Cheatsheet
This time, you will be learning Git and Github and how to use them

### What is Git
Git is a distributed version control tool made by Linus Torvalds that enables developers to keep track of 
the latest changes in the code that they are working with.

### Setting Up a Repository (Repo)
A Git repo is a storage of your code that allows you to save changes as you work and access them when you need to.

### Initializing a New Git Repo
To initialize a new repo use the command below:

```git init```

what this command does is to create a new ___.git___ subdirectory in your current working directory and a ___master branch___

### Cloning an Existing Repo
Git init handles directly initializing Git in your own project. What if the project has already been created and and you
want to work on it; you clone it using the command below:

```git clone <repo url>```

The git clone command copies the remote repository to your local disk and in a folder bearing the name of remote repo.

### How To Save Changes To Your Repo
After making changes in your files, in order to add your changes to git, you can use the following command:

```git add .``` or ```git add <file name>```

the first command will add all changes on all files while the second will add the changes on the specified file alone.
After adding you changes you will need to commit them. Commiting changes gives you the opportunity to make comments that
other people who are working on the project can read in order to understand what you are doing or have done.

### Making Your Code Remote
In order for other people to be able to see your code, the changes you have made and contrubute to them, your code needs to
be hosted remotely and that is where Github comes in.
Github is a Git repository hosting service. Many of its features are free for developers and it sup

### To check status of file
To check the status of files you’ve changed in your working directory, i.e, what all has changed since your last commit.

```git status```

### Push or Pull your changes to remote.
If you have added and committed your changes and you want to push them. Or if your remote has updated and you want those latest changes.

```git pull <remote> <branch>```

and to push to remote

```git push <remote> <branch>```

### Listing out Branches.
If you want to list out all the branches, be it the master or any any other.


```git branch``` or ```git branch -a```
