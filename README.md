# Using This Template

## 1. Clone the Repository

```bash
git clone https://github.com/josephdaniel8805/Mern-Template.git your_project_name
```

---

## 2. Move Into Project Folder

```bash
cd your_project_name
```

---

## 3. Remove Existing Git History

### PowerShell

```powershell
Remove-Item -Recurse -Force .git
```

---

## 4. Initialize a New Git Repository

```bash
git init
```

---

## 5. Add Files and Create First Commit

```bash
git add .
git commit -m "first commit"
```

---

## 6. Rename Branch to Main

```bash
git branch -M main
```

---

## 7. Add Your New GitHub Repository

```bash
git remote add origin YOUR_NEW_REPO_URL
```

Example:

```bash
git remote add origin https://github.com/yourusername/your-repo-name.git
```

---

## 8. Push to GitHub

```bash
git push -u origin main
```
