# Git Trek: The Version Control Voyage

## Objective
Learn basics of Git version control by simulating a space mission with Captain Kirk and the crew.

## Instruction
Clone this repository and write your name, linkedin profile link, and year (You are free to choose which year you want) and create own branch name.

## Starter

```
git config --global user.name “[username]”
git config --global user.email [email]

```
## Some Commands that you can use for this activity (Member)

create own branch 

```
git clone https://github.com/nikxherrera/PortfolioSample.git
git pull origin main
git checkout 
```
Edit the code
```
git status
git add .
git commit -m "[message]"
git push -u origin [branch name]
```
Send pull request and merge

## Commands for public repo (Non- Member) (The user must have an account already)

fork the repository
```
git remote add upstream https://github.com/nikxherrera/Get-to-know.git
git fetch upstream

```
edit the file and create own branch

```
git checkout -b "name-of-branch" or git branch "name-of-branch"
git checkout "name-of-branch"

```

```
git add .
git commit -m "commit message"
git push origin branch-name
```

