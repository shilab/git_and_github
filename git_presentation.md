class: center, middle

# An Introduction to Git and GitHub

Andrew Quitadamo

---

# Overview

*   What is Git?

--

*  What is GitHub?

--

*  Git Basics

--
*  Collaborating on GitHub

---
name: git

# What is Git?  

*  Git is a Distributed Version Control System  

--

*  It tracks changes to files and stores them  

--

*  It allows you to revert file changes, view differences in file versions

---
# Where to get Git

*  [Git Download](http://git-scm.com/downloads)

*  [Git GUI Clients](http://git-scm.com/downloads/guis)

---

name: GitHub

# What is GitHub

*  GitHub is a web based repository host for Git.  

--

*  GitHub adds a web-based interface for Git. 

--

*  It adds functionality like forking, and pull requests which contribute to a collaborative model.

---

# Git Basics

*  To create a new repository, cd into the directory and type:
```
git init
```

--

*  You can also clone a remote repository, like the one this presentation is on:
```
git clone https://github.com/shilab/git_and_github.git
```

--

*  To add files for git to track:
```
git add <file>
```

--

*  To commit the file to the repository:
```
git commit -m 'Commit message'
```
The commit message details what you have changed. 

---

# Git Basics

* You can push the changes back to GitHub:
```
git push origin <branch>
```
Where ```<branch>``` is the branch you are working from.

*  Branches can be used to isolate changes.  

--

*  The master branch is the default branch, and new branches can be created from it.

--

*  You can use a branch for developing a feature and then merge it back into the master branch.
---

# Git Branches

*  To create a branch:  
```
git checkout -b <new_branch>
```

--

*  Switch back to master:
```
git checkout master
```

---

#Git Basics

* Update your local repository
```
git pull
```

--

*  To see the repository history
```
git -log
```


