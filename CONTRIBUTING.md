# Contributing to Encore

## Branches
- main → stable production
- dev → ongoing development
- feature/* → new features

## Git Rules
- Commit message format: "type: short description"
- Types: feat, fix, docs, refactor, test, chore

## Workflow
1. Pull the latest changes: `git pull origin dev`
2. Create a new feature branch: `git checkout -b feature/xyz`
3. Make your changes
4. Commit your changes: `git add . && git commit -m "feat: XYZ"`
5. Push to GitHub: `git push origin feature/xyz`
6. Open a Pull Request against `dev`
7. Team reviews → merge to `dev` → eventually merged to `main`
