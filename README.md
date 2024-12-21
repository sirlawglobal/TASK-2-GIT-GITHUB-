# TASK-2-GIT-GITHUB-
This is the second task in web3  learning track of teachable internship..this is cool


# Version Control

Version control is a system that helps developers track and manage changes to their codebase. It allows multiple people to collaborate on a project, keeps a history of changes, and makes it easy to revert to previous versions.

---

## Git vs GitHub

| **Feature**         | **Git**                                       | **GitHub**                                   |
|----------------------|-----------------------------------------------|----------------------------------------------|
| **Definition**       | A version control system to manage code history locally. | A cloud-based platform for hosting Git repositories. |
| **Usage**            | Tracks changes and supports collaboration locally. | Facilitates sharing and collaboration online. |
| **Scope**            | Command-line tool.                           | Web-based interface with additional features. |

---

## GitHub Alternatives

1. **GitLab**  
2. **Bitbucket**  
3. **SourceForge**  

---

## Git Fetch vs Git Pull

| **Command**     | **Description**                                                                                  |
|------------------|--------------------------------------------------------------------------------------------------|
| `git fetch`     | Downloads changes from the remote repository but does not apply them to the working directory.   |
| `git pull`      | Combines `git fetch` and `git merge` to download and integrate changes into the current branch.   |

---

## Git Rebase (Simplified)

Rebasing is a way to integrate changes from one branch into another. Unlike merging, it rewrites commit history to create a linear sequence of commits.

**Command**:  
```bash
git rebase <branch>
