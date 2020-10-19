# Git for Source/Version Control

Git is a great tool for managing code. It was created by Linus Torvalds (yes the very same Linus who created the Linux kernel) and is now the defacto standard for source/version control for possibly all applications written today. There really isn't a better tool on the market than Git. This guide assumes you have setup Git already and is covered in our guides on settng up your workstation which can be found here [[Link]].

The first few things people trip over when learning Git is that there are some odd concepts if you've only ever used normal files on a file server (or your local computer) to store code/playbooks/etc. We will take a more practical approach to learning Git and show how its used and why and then inject the main parts after a good solid understanding has been obtained. Git works in what is called a repo, which is short for repository. Going on that, we see that all our code we will be working on will live in a repository. Pretty straightforward. To create a repository, all one needs to do is run `git init` in a folder on their system where they wish to start a repository. We do not recommend using any of the main User folders that are your machine (C:\users\you, /Users/you, /home/you). Instead create a folder inside of there called Working and move into that directory. Now you may safely run `git init`. You will see a line that says something like this depending on the OS of your workstation:

## Linux
`Initialized empty Git repository in /home/kwalker/Working/.git/`

## OSX
`Initialized empty Git repository in /Users/kwalker/Working/.git/`

## Windows
`Initialized empty Git repository in /home/kwalker/Working/.git/`

Once this is done you can now start creating code/files and adding them to the repository. You may be wondering, "I just created a repository via that `git init` command, why do I now have to add things to the repository? Shouldn't anything created in this folder be part of the repository?". And from a normal workview, yes that is what should happen. However Git was created in the spirit of how Linux was created and works. And in a Linux environment it only does what its told to do explicitly. So we do have an extra step as we work on things in a Git repository to make it accept our files. All that needs to be done (initially, don't do this going forward as its bad practice) is `git add .`. This should only be done when adding an existing folder/project to a newly created Git repository. You can explicilty add files to the Git repository via `git add filename`.
