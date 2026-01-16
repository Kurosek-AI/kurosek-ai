# Git Basics Tutorial

Welcome to the Git Basics Tutorial!  
This tutorial will help you understand the basic workflow of Git: add, commit, and push.

## 1. Overview of Git Workflow
Working Directory  -->  Staging Area  -->  Local Repository  -->  Remote Repository (GitHub) (File baru/ubah)       (git add)         (git commit)           (git push)
- **Working Directory**: tempat kamu menulis kode / membuat folder baru
- **Staging Area**: menandai perubahan untuk commit
- **Local Repository**: menyimpan commit secara lokal
- **Remote Repository**: GitHub, tempat orang bisa lihat jika public

## 2. Common Git Commands

| Command | Description | Example |
|---------|------------|---------|
| `git status` | Check changes | `git status` |
| `git add <file>` | Add file to staging area | `git add README.md` |
| `git add .` | Add all changes | `git add .` |
| `git commit -m "msg"` | Save snapshot locally | `git commit -m "Add example file"` |
| `git push origin main` | Push commit to GitHub | `git push origin main` |
| `git pull origin main` | Pull updates from GitHub | `git pull origin main` |

## 3. Step-by-Step Example

1. Create a new file: `example.txt`  
2. Check changes: `git status`  
3. Add changes: `git add example.txt`  
4. Commit changes: `git commit -m "Add example.txt"`  
5. Push to GitHub: `git push origin main`  

## 4. Tips

- Commit sering & jelas  
- Use `.gitignore` for temporary files  
- Check `git log` to see commit history
