# Git Basic Commands 🚀

Git ek powerful **version control system** hai jo developers ko **code manage karne** aur **track changes** karne me madad karta hai. Yeh `README.md` file Git ke **most used commands** ko cover karti hai.

---

## 🔹 1. Initializing & Configuration  
| Command | Description |
|---------|------------|
| `git init` | Initialize a new Git repository |
| `git config --global user.name "Your Name"` | Set global username |
| `git config --global user.email "you@example.com"` | Set global email |

---

## 🔹 2. Repository & File Management  
| Command | Description |
|---------|------------|
| `git clone <repo_url>` | Clone an existing repository |
| `git status` | Check the status of your repository |
| `git add <file>` | Stage a specific file |
| `git add .` | Stage all changes |
| `git commit -m "Message"` | Commit staged changes with a message |
| `git rm --cached <file>` | Unstage a file |

---

## 🔹 3. Branching & Merging  
| Command | Description |
|---------|------------|
| `git branch` | List all branches |
| `git branch <branch_name>` | Create a new branch |
| `git checkout <branch_name>` | Switch to another branch |
| `git merge <branch_name>` | Merge a branch into the current branch |
| `git branch -d <branch_name>` | Delete a branch |

---

## 🔹 4. Remote Repositories  
| Command | Description |
|---------|------------|
| `git remote -v` | Show remote repositories |
| `git push origin main` | Push changes to the main branch |
| `git pull origin main` | Pull latest changes from the main branch |
| `git fetch` | Fetch updates from remote |

---

## 🔹 5. Undoing Changes  
| Command | Description |
|---------|------------|
| `git reset --hard` | Reset all changes |
| `git checkout -- <file>` | Discard changes in working directory |
| `git revert <commit_id>` | Undo a specific commit |
| `git stash` | Temporarily save changes |
| `git stash pop` | Restore last stashed changes |

---

### 🎯 **Why Use Git?**
✔️ **Version Control** - Code ki changes ko track karna easy hota hai.  
✔️ **Collaboration** - Multiple developers ek sath kaam kar sakte hain.  
✔️ **Branching & Merging** - Experiment karne ke liye alag branches create kar sakte hain.  
✔️ **Backup & Security** - Code remote repository me save rehta hai.  

---

### 🔗 **Helpful Git Resources**
📖 [Official Git Documentation](https://git-scm.com/doc)  
📘 [GitHub Learning Lab](https://lab.github.com/)  

🚀 **Happy Coding with Git!** 😊
