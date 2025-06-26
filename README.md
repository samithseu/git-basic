# Git Basic Commands 🤏

<p align="left">
  <span>Language 🔤 </span>
  <a>English</a> &nbsp; | &nbsp;
  <a href="README_KH.md">ភាសាខ្មែរ</a>
</p>

## 1️⃣ Clone A Remote Repository

### From GitHub

```bash
git clone [repo_url]
# Example: git clone https://github.com/samithseu/git-basic.git
```

### From GitLab

```bash
git clone [repo_url]
# Example: git clone https://gitlab.com/vuejs9055841/using-i18n.git
```

---

## 2️⃣ Push From Local To Remote Repository

### Initialize a local git repo

```bash
git init
```

### Check Status

```bash
git status
```

### Track files

```bash
git add [file_name(s)]
# Example1: git add index.html style.css
# Example2: git add . (for adding all new changed files)
```

### Commit files with messages

```bash
git commit -m [messages]
# Example: git commit -m "initial commit"
```

### Create and change branch

```bash
git branch -M [branch_name]
# Example: git branch -M main
```

### Add remote repo to a local repo

```bash
git remote add [remote_name] [repo_url]
# Example: git remote add origin https://github.com/samithseu/git-basic
```

### Push to remote repo

```bash
git push [remote_name] [branch_name]
# Example: git push origin main
```
