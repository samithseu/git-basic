# Commands មូលដ្ឋានសម្រាប់ Git

<p align="left">
  <a href="README.md">English</a> &nbsp; | &nbsp;
  <a href="README_KH.md">ភាសាខ្មែរ</a>
</p>

## ចម្លង ឬទាញយក Repo ពី Internet (Remote) មកប្រើក្នុង Computer (Local)

### ពី GitHub

```bash
git clone [URL របស់ Repo]
# ឧទាហរណ៍: git clone https://github.com/samithseu/git-basic.git
```

### ពី GitLab

```bash
git clone [URL របស់ Repo]
# ឧទាហរណ៍: git clone https://gitlab.com/vuejs9055841/using-i18n.git
```

---

## បង្ហោះកូដពី Computer ទៅរក្សាទុកលើ Internet (Remote Repo)

### បង្កើត Repo សម្រាប់ Computer (Local)

```bash
git init
```

### ឆែកមើល Files ដែលបានប្រែប្រួលដូចជា៖ (បង្កើត,កែ,លុប)

```bash
git status
```

### ជ្រើសរើស Files សម្រាប់រក្សាជា Commit

```bash
git add [ឈ្មោះ file (អាចលើសពី1)]
# ឧទាហរណ៍: git add index.html style.css
# ឧទាហរណ៍: git add . (សម្រាប់បន្ថែមរាល់ files ថ្មីៗដែលបានប្រែប្រួល)
```

### រក្សាមាតិការបស់ Files ដែលបានជ្រើសរើស ឱ្យទៅជា Commit នៅលើ Computer (Local)

```bash
git commit -m [សារដែលយើងចង់សរសេរ]
# ឧទាហរណ៍: git commit -m "initial commit"
```

### បង្កើត និងផ្លាស់ប្ដូរ Branch

```bash
git branch -M [ឈ្មោះ Branch]
# Example: git branch -M main
```

### បន្ថែម Remote Repo ដើម្បីភ្ជាប់ជាមួយនឹង Local Repo ក្នុង Computer

```bash
git remote add [ឈ្មោះ Remote] [URL របស់ Repo]
# ឧទាហរណ៍: git remote add origin https://github.com/samithseu/git-basic
```

### បង្ហោះកូដទៅលើ Remote Repo

```bash
git push [ឈ្មោះ Remote] [ឈ្មោះ Branch]
# ឧទាហរណ៍: git push origin main
```
