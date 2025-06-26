# Git Basic Commands 🤏

<p align="left">
  <span><img height=14 src="https://github.com/user-attachments/assets/3cd10117-9624-48fa-b8aa-429382734ede" alt="choosing language" /> </span>
  <a>English</a> &nbsp; | &nbsp;
  <a href="README_KH.md">ភាសាខ្មែរ</a>
</p>

## 1. Clone A Remote Repository

### 1.1. From GitHub

```bash
git clone [repo_url]
# Example: git clone https://github.com/samithseu/git-basic.git
```

### 1.2. From GitLab

```bash
git clone [repo_url]
# Example: git clone https://gitlab.com/vuejs9055841/using-i18n.git
```

---

## 2. Push From Local To Remote Repository

### 2.1 Initialize a local git repo

```bash
git init
```

### 2.2. Check status

```bash
git status
```

### 2.3 Track files

```bash
git add [file_name(s)]
# Example1: git add index.html style.css
# Example2: git add . (for adding all new changed files)
```

### 2.4. Commit files with messages

```bash
git commit -m [messages]
# Example: git commit -m "initial commit"
```

### 2.5. Create and change branch

```bash
git branch -M [branch_name]
# Example: git branch -M main
```

### 2.6. Add remote repo to a local repo

```bash
git remote add [remote_name] [repo_url]
# Example: git remote add origin https://github.com/samithseu/git-basic
```

### 2.7. Push to remote repo

```bash
git push [remote_name] [branch_name]
# Example: git push origin main
```
