Encore Team Quick Start Guide
1️⃣ Clone the Repo
git clone git@github.com:Felix-Arc/encore-app.git
cd encore-app


This downloads the project to your local machine

2️⃣ Checkout Dev Branch
git checkout dev


All development happens on the dev branch

main stays stable → never commit directly to main

3️⃣ Create a Feature Branch
git checkout -b feature/your-feature-name


Example: feature/login or feature/feed-animation

This branch is isolated, safe to experiment

4️⃣ Work & Commit
git add .
git commit -m "feat: Short description of your change"


Commit messages must follow format: type: description

Types: feat, fix, docs, refactor, test, chore

5️⃣ Push Your Feature Branch
git push origin feature/your-feature-name


Uploads your branch to GitHub

6️⃣ Open a Pull Request (PR)

Go to GitHub → create PR from your feature branch → target branch dev

Team reviews → merge to dev

7️⃣ Keep Your Branch Updated
git checkout dev
git pull origin dev
git checkout feature/your-feature-name
git merge dev


Always keep your branch updated with latest dev changes

✅ Quick Notes

Always work on a feature branch, never directly on dev or main

Use clear commit messages

Pull Requests are required for review before merging