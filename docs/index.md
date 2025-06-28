# How to Use GitHub Desktop for Beginner

## 1. Introduction

**GitHub Desktop** is a user-friendly graphical interface that simplifies working with Git and GitHub repositories. It allows users to manage repositories, perform commits, resolve conflicts, and synchronize code with GitHub—all without using the command line.

### Why It Matters

For beginners, the Git command-line interface can be intimidating. GitHub Desktop bridges that gap by providing a visual and intuitive way to use Git and GitHub. It is especially helpful for those new to version control, enabling them to focus on collaboration and code without needing deep technical knowledge of Git commands.

### Who This Guide Is For

- Beginner developers learning Git and GitHub  
- Students working on coding assignments or group projects  
- Non-technical contributors (e.g., designers, technical writers) collaborating on documentation or files in GitHub  
- Teams looking for a simplified Git GUI to ease onboarding  

---

## 2. Key Terminology

| Term                   | Description                                                                         |
|------------------------|-------------------------------------------------------------------------------------|
| **Repository (Repo)**  | A storage space for your project code and files.                                    |
| **Clone**              | Creating a local copy of a remote repository.                                       |
| **Commit**             | A snapshot of changes made to files.                                                |
| **Push**               | Sending local commits to a remote repository (GitHub).                              |
| **Pull**               | Fetching changes from the remote repository to your local machine.                  |
| **Branch**             | An independent line of development in a repository.                                 |
| **Merge**              | Combining changes from one branch into another.                                     |
| **Pull Request (PR)**  | A request to merge changes into a branch, often reviewed by others before approval. |

---

## 3. Technical Overview

GitHub Desktop is built using **Electron**, a framework that allows cross-platform desktop apps using web technologies. It acts as a wrapper around Git, providing a graphical interface to Git operations.

### Key Features

- Clone repositories from GitHub.com  
- Create, switch, and delete branches  
- Commit changes with messages  
- Visual diffing of file changes  
- Push and pull updates  
- Resolve merge conflicts visually  
- Open repository in external editors like VS Code  

### Mermaid Diagram: Basic Workflow

```mermaid
    A[GitHub Repository] -->|Clone| B[Local Repository]
    B -->|Make Changes| C[Modified Files]
    C -->|Commit| D[Local Commits]
    D -->|Push| A
    A -->|Pull| B
```
![Github workflow](<assests/github flowchart.png>){ width="400px" style="border: 1px solid #ccc; border-radius: 8px;"}

## Tools and Technologies Involved

- **Git**: Underlying version control system  
- **GitHub**: Cloud hosting for Git repositories  
- **Electron**: Framework for cross-platform GUI  
- **Markdown**: Format for README files and documentation  
- **Text Editor (e.g., VS Code)**: To modify source files  

---

## 4. Step-by-Step Guide or Workflow

### Step 1: Install GitHub Desktop

- Visit the [GitHub Desktop website](https://desktop.github.com)  
- Download the installer for your operating system (Windows/macOS)  
- Run the installer and follow the installation steps  

### Step 2: Sign In to GitHub

- Open GitHub Desktop  
- Click on **Sign in to GitHub.com**  
- A browser window opens  
- Authorize the app using your GitHub credentials  
- GitHub Desktop will be linked to your GitHub account  

### Step 3: Clone a Repository

- In GitHub Desktop: **File > Clone repository**  
- Select a repo from your GitHub account or enter a URL  
- Choose a local path to save it  
- Click **Clone**  

### Step 4: Make Changes Locally

- Open the cloned folder in your editor (e.g., VS Code)  
- Modify files (e.g., `README.md`)  
- Save the changes  

### Step 5: Commit Changes

- Return to GitHub Desktop  
- View changes under the **Changes** tab  
- Add a summary message  
- Click **Commit to main** (or your current branch)  

### Step 6: Push Changes to GitHub

- Click **Push origin** (top right)  
- Your changes are now live on GitHub  

### Step 7: Pull Remote Changes

- Click **Fetch origin**  
- Then click **Pull origin** to sync with the remote  

### Step 8: Create and Merge Branches (Optional)

**To create a new branch:**

- Click the branch dropdown  
- Click **New Branch**, name it, and click **Create Branch**  

**To merge branches:**

- Switch to the `main` branch  
- Click **Branch > Merge into Current Branch**  
- Select the feature branch  

---

## 5. Best Practices

- **Commit often**: Keep commits small and focused  
- **Use clear commit messages**: Explain what & why  
- **Pull before push**: Prevent merge conflicts  
- **Don’t commit secrets**: Avoid pushing passwords or keys  
- **Use branches**: Keep features/fixes isolated  
- **Check the diff before committing**: Avoid mistakes  

---

## 6. Common Issues & Troubleshooting

| Issue                    | Solution                                                           |
|--------------------------|--------------------------------------------------------------------|
| Cannot push changes      | Ensure you're authenticated and have permission                   |
| Merge conflicts          | Use GitHub Desktop’s visual tool or resolve in an editor          |
| Repo not showing up      | Make sure you're logged into the correct GitHub account           |
| Changes not appearing    | Ensure files are saved and in the cloned repo                     |
| Commit button is greyed out | Make sure you've made changes and entered a message           |

---

## 7. References

- [GitHub Desktop Official Docs](https://docs.github.com/en/desktop)  
- [GitHub Learning Lab](https://lab.github.com)  
- [Git Basics](https://git-scm.com/docs)  
- [Pro Git Book](https://git-scm.com/book/en/v2)  

---

## 8. Appendix

### Sample Commit Message Format

```
feat: add introduction section to README

- Added overview and target audience
- Explained why GitHub Desktop is useful
``` 

### Useful Keyboard Shortcuts

| Action           | Shortcut                                |
|------------------|------------------------------------------|
| Commit changes   | Ctrl + Enter (Win) / Cmd + Enter (Mac)   |
| Open in Editor   | Ctrl + Shift + A                         |
| Switch branch    | Ctrl + B                                 |
| Fetch updates    | Ctrl + Shift + F                         |
