
Git Demo Repository
===================

Welcome to the git demo repository!

This repo contains a few branches that you can play around with and explore.

Moving around branches
----------------------

To see all your local branches:

    git branch

To see all the remote branches:

    git branch -r

To check out a local copy of a remote branch:

    git checkout -b new-feature origin/new-feature

To switch to one of your local branches:

    git checkout new-feature
    git checkout master # etc.

To create a new local branch and switch to it:

    git checkout -b my-new-feature


What branches are there? What are the contents of each one?


Adding lines
------------

In this patch, we add some lines to the end of the README.md file.
These are the lines we're adding.
You can see a `+` next to each one in the patch via `git show HEAD`.
