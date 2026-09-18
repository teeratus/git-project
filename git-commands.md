# Git Commands

copy from www/git-project/git-commands.md

Repository URL:
URL ของ repository:

```bash
https://github.com/teeratus/command.git
git@github.com:teeratus/command.git
```

## create a new repository
Create a new repo on the command line.
สร้าง repository ใหม่จาก command line

```bash
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:teeratus/command.git
git push -u origin main
```

## push an existing repository
Push an existing local repo to GitHub.
ส่ง repository ที่มีอยู่แล้วขึ้น GitHub

```bash
git remote add origin <repository-url>
git branch -M main
git push -u origin main
```

## clone an existing repository
Clone a repo from GitHub.
clone repository จาก GitHub

```bash
git clone <repository-url>
git clone https://github.com/teeratus/command.git
git clone git@github.com:teeratus/command.git
```

## pull
Use `git pull` when remote has new changes.

```bash
git pull
```

Use `git pull --rebase` when local and remote have diverged.

```bash
git pull --rebase
```

`Outgoing Changes` and `Incoming Changes` mean both sides have new commits.
`Outgoing Changes` และ `Incoming Changes` หมายถึงทั้งสองฝั่งมี commit ใหม่
