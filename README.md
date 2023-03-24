W3SCHOOLS TUTORIAL FOR GIT AND GITHUB

This repository is a test based on tutorial given by W3Schools git and github
tutorials, found (https://www.w3schools.com/git/default.asp). 

....

Git GitHUB Fork

Add to someone else's repository
Fork a Repository

Log in to GitHub and fork repository https://github.com/w3schools-test/w3schools-test.github.io/

now we have our own fork but only on GitHub: sis-I/w3schools-test.github.io

~ a clone is a full copy of a repository.
~ move back to original (https:://github.com/w3schools-test/w3schools-test.github.io) repository, to clone

~ Open Git bash in local machine and clone the repository

$ git clone https://github.com/w3schools-test/w3schools-test.github.io.git

~ you will see a new directory named after the cloned project:

$ ls
$ cd w3schools-test.github.io
$ git status
$ git log

~ To clone to specific folder,
$ git clone https://github.com/w3schools-test/w3schools-test.github.io.git <forldername>

~ Configuring Remotes
$ git remote -v
~ rename the original origin remote: to upstream
$ git remote rename origin upstream
$ git remote -v
~ Then fetch the url of our own fork (sis-I/w3schools-test.github.io)
~ and add that as origin:
$ git remote add origin git@github.com:sis-I/w3schools-test.github.io.git
$ git remote -v 
~ now we can see origin and upstream repositories
~ We have two remotes
* origin- our own fork, we got full access
* upstream - original repo, only read-only access
