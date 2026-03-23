# MPC Homework Repo

## First-time GitHub setup

Create an empty GitHub repository under the `man-ella` account, then run:

```powershell
git remote add origin https://github.com/man-ella/MPC_Project.git
git add .
git commit -m "Initial homework setup"
git push -u origin main
```

## Daily workflow on your computer

Pull latest changes:

```powershell
git pull origin main
```

Save your new changes:

```powershell
git add .
git commit -m "Describe what changed"
git push origin main
```

## Workflow in Google Colab

Clone the repo:

```python
!git clone https://github.com/man-ella/MPC_Project.git
%cd MPC_Project
```

Pull the newest changes in Colab:

```python
!git pull origin main
```

If you want to push from Colab, set your Git identity first:

```python
!git config --global user.name "man-ella"
!git config --global user.email "YOUR_GITHUB_EMAIL"
```

Then commit and push:

```python
!git add .
!git commit -m "Update from Colab"
!git push origin main
```

## Notes

- Track the notebook and handwritten code.
- Ignore generated files such as datasets and trained models unless you explicitly want them in Git.
- Pull before starting work if you changed files somewhere else.
