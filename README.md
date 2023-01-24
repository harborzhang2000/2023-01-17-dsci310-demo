# 2023-01-17: DSCI310 Git Demo

Intro-Git

- `git clone <URL>`: takes what's on github and does a one time download to your computer
- `git add <FILE>`: add the <FILE>s to the staging area
- `git commit`: create the commit (aka snapshot)
  - `git commit -m "MESSAGE"`:create the git message directly in the command line

- `git push <where> <what>`: take local commits on `<what>`, and send it to `<where>`
    - e.g., `git push origin main`
- `git pull <where> <what>`: take remote commits on `<what>`, and pull it from `<where>`
    - e.g., `git pull origin main`
- `git push origin main`: send code from branch `main` local computer to the remote `origin`

## Branches

- `git branch <name>`: create a branch named <branch> where ever you are (`HEAD`)
- `git switch <name>`: go to that branch
  - `git checkout <name>`: older way to move to branch 
- `git switch -c <name>`: create a branch and move to it in 1 command
  - `git checkout -b <name>`: same thing using `checkout`