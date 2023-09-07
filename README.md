# Git push from Ubuntu Terminal
[Notion Link](https://www.notion.so/Git-push-from-Ubuntu-Terminal-4eac4f305f694e52a257444051632274?pvs=21)

# Git installation

```bash
sudo apt-get update
```

```bash
sudo apt-get install git
```

```bash
git config --global user.name "****"
git config --global user.email "****"
```

# Git init

Go to the required Directory 

```bash
cd <path>/repo
```

```bash
git init
```

![Untitled](README_files/Untitled.png)

```bash
git remote add origin https://github.com/Lozsku/Alpha.git
```

```bash
git add .
```

```bash
git commit -m 'commit_message'
```

```bash
git branch -M main
```

```bash
git push -u origin main
```

It would automatically ask you for your username and password for GitHub. After entering the details, go to GitHub and refresh. The files would get added there.

`Username for 'https://github.com' your_username` 

`Password for 'https://your_username@github.com' : *******`

But GitHub is no longer accepting account passwords when authenticating Git operations. You need to add a **PAT (Personal Access Token)** instead, and you can follow the below method to add a PAT on your system.

# **Create Personal Access Token on GitHub**

From your GitHub account, go to **Settings** → **Developer Settings** → **Personal Access Token** → **Tokens** (classic) → click **Generate token** (classic)→ **Fillup the form** → **Copy the generated Token**, it will be something like `ghp_sFhFsSHhTzMDreGRLjmks4Tzuzgthdvfsrta`

# Git Pull

```bash
git pull origin
```

# Git Push

```bash
git add .
```

```bash
git commit -m "Your commit message"
```

```bash
git push origin
```

`Username for 'https://github.com' your_username` 

`Password for 'https://your_username@github.com' : PAT(personal access token)` 

# Git Log

```bash
git log
```

```bash
git log --oneline
```
