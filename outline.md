# Intro

## What is git?

* Distributed version control system (DVCS).
* Competes with subversion, mercurial and a few others.

## What does it do?

* Saves snapshots (commits) of work in a timeline.
* Provides *really* powerful tools to interact with this timeline.

## What is GitHub?

* A popular website for storing and collaborating on projects that use git.
* Not owned/run/created by the same people who created git. Just shares a similar name.
* *Perfectly possible to use git and not GitHub*.
* Competes with bitbucket.

## Why is git awesome?

* Branching.
* Try an idea out and get rid of it without losing work.
* Jump to any point in the timeline.
* Merging/Rebasing.
* Blaming.
* ...a million other reasons

## Why should you use it?

* Collaboration.
* Visibility.
* Saving yourself from epic losses of data!

# Using git - One-person workflow.

## Creating a repository

Git works with 'repositories'. This is just a folder where your code is.

    git init

Creates a folder called `.git` where the magic happens. **Never delete this folder! EVER!**

## Stages of a file

Create -> Edit -> Stage -> Commit -> Push

### Create

* Just create a file in the project.

### Edit

* Edit the file. Type some text.

### Stage

    git add <filename>

or

    git add .

### Commit

    git commit -m 'Some information about the changes made'

### Push

    git push origin master