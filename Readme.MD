# Heat and Health Project

This repository is used for our collaborative Heat and Health analysis project.

Each member has their own Git branch to work on independently. Please push your changes to your assigned branch rather than directly to `main`.

## Team Branches

| Member | Branch |
| :--- | :--- |
| Jeet | `jeet` |
| Aidan | `aidan` |
| Akshay | `akshay` |
| Rookie | `rookie` |
| Jacques | `jacques` |

## 1. Initial Git Setup

Install Git if you haven't already:

https://git-scm.com/downloads

Configure Git with your name and GitHub email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Clone the repository:

```bash
git clone https://github.com/jpmehta1/Heat-and-Health-Project.git
cd Heat-and-Health-Project
```

Fetch the latest branches:

```bash
git fetch origin
```

Switch to your assigned branch. For example, Aidan would run:

```bash
git switch aidan
```

If your branch isn't available locally yet, run:

```bash
git switch --track origin/aidan
```

Replace `aidan` with your own branch name.

## 2. Working on the Project

Before starting any work, make sure you're on your branch:

```bash
git branch --show-current
```

Get the latest changes from your branch:

```bash
git pull origin aidan
```

Now make changes to your files, notebooks, or scripts.

## 3. Pushing Your Changes

Once you've finished making changes:

Check which files were modified:

```bash
git status
```

Stage your changes:

```bash
git add .
```

Commit your changes:

```bash
git commit -m "Added initial analysis"
```

Push your changes to your branch:

```bash
git push origin aidan
```

Replace `aidan` with your own branch name.

You can repeat this process every time you make changes.

## 4. Getting Updates from Main

If other members have added changes to `main`, you can bring those updates into your branch.

```bash
git switch aidan
git fetch origin
git merge origin/main
```

If Git reports a merge conflict, resolve it before committing further changes.

## 5. Merging Your Work into Main

Once your work is ready:

1. Push your latest changes to your branch.
2. Open the repository on GitHub.
3. Go to **Pull requests**.
4. Select **New pull request**.
5. Set the base branch to `main` and compare branch to your own.
6. Create the pull request so the team can review it.

After approval, the changes can be merged into `main`.

## Important Rules

1. **Do not push directly to `main`.** Always work on your own branch.
2. Pull the latest updates before beginning work.
3. Write meaningful commit messages so others understand your changes.
4. Avoid editing another person's files simultaneously when possible.
5. Do not commit passwords, API keys, or unnecessary large data files.

## Quick Reference

For everyday work, these are the main commands you'll need:

```bash
git switch your-branch
git pull origin your-branch

# Make your changes

git add .
git commit -m "Describe your changes"
git push origin your-branch
```

Replace `your-branch` with your assigned branch name.

**Repository:** https://github.com/jpmehta1/Heat-and-Health-Project
