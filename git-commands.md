# Git Commands

```bash
// https URL for the repository
https://github.com/teeratus/command.git

// SSH URL for the repository
git@github.com:teeratus/command.git
```

## create a new repository on the command line

```bash
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:teeratus/command.git
git push -u origin main
```

## push an existing repository from the command line

```bash
git remote add origin <repository-url>

git remote add origin git@github.com:teeratus/command.git
git branch -M main
git push -u origin main
```

## clone an existing repository

```bash
git clone <repository-url>

// Example using HTTPS
git clone https://github.com/teeratus/command.git

// Example using SSH
git clone git@github.com:teeratus/command.git

```

## pull with rebase

Outgoing Changes และ Incoming Changes อยู่พร้อมกัน แปลว่ามีทั้ง commit ที่ยังไม่ push และ commit จาก GitHub ที่ยังไม่ pull ครับ ดังนั้น git pull --rebase มักจะเป็นตัวที่เหมาะกว่า

```bash
git fetch
git pull --rebase
```