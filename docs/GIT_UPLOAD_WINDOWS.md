# Upload this repository from Windows using Git

## Before you start
- Install Git for Windows from https://git-scm.com/download/win if `git --version` does not work.
- Create an empty repository on GitHub named `paperclip-agent-skills`.
- Extract the ZIP and open PowerShell inside the extracted `paperclip-agent-skills` folder.
- Do not upload API keys, `.env` files, customer data, or credentials.

## First upload (PowerShell)
Replace `YOUR-GITHUB-USERNAME` with your actual GitHub username. Use the exact repository URL shown on GitHub.

```powershell
git init
git branch -M main
git add .
git status
git commit -m "Initial Paperclip agent skills library"
git remote add origin https://github.com/YOUR-GITHUB-USERNAME/paperclip-agent-skills.git
git push -u origin main
```

If Git asks you to authenticate, complete the browser sign-in flow or use an approved Git Credential Manager method. Do not paste a personal access token into chat or commit it to a file.

## If `git commit` says identity is unknown
Set the name and email you want associated with your commits:

```powershell
git config --global user.name "Your Name"
git config --global user.email "YOUR-GITHUB-NOREPLY-OR-ACCOUNT-EMAIL"
```

Then retry `git commit`.

## If the GitHub repository is not empty
If you created a README, license, or other file on GitHub first, the remote has a separate initial commit. Avoid force-pushing. The simplest beginner-safe path is to create a new empty repository, or carefully pull/reconcile the remote history before pushing.

## Updating the repository later
Run these commands from the same local folder after editing files:

```powershell
git status
git add .
git diff --cached
git commit -m "Describe the skill update"
git push
```

Review `git diff --cached` before committing. Use a branch and pull request for skill changes when possible; do not auto-merge unreviewed skills.
