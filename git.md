# Git

## One Time Setup

`git config --global user.name "Ben McMann"`
`git config --global user.email "bbmcmann@volosys.com"`

## Project Setup

`git init`

## 3 Steps Repeating Commit Process
1. Make changes to code
2. Stage related changes
    * git add
3. Commit chnages with a message
    * git commit -m "Message"

## Commands

* status -> tells what files have been staged or committed
* add -> add a file to the stage
* ls -a -> see hidden files
* rm --cached -> remove file from stage
* git commit -m "Present tense description of what changed"
* git log -> shows history of commits. enter to move down, q to quit.
* git checkout -- fileName -> discard current changes


## Problems
* commit without -m -> Use Esc :wq to quit vim
* wrong message -> git commit --amend -> "new message"