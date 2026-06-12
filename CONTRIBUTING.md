# Contributing Guide

## 1. Fork or Clone the Repository

If you are a collaborator:
```bash
git clone https://github.com/imamelihuseynov/university_repo.git
cd university_repo
```

If you are not a collaborator, fork the repo first, then clone your fork.

## 2. Create a Branch

Always create a new branch before making changes:
```bash
git checkout main
git pull origin main
git checkout -b type/short-description
```

Branch types: `feat`, `fix`, `docs`, `refactor`, `chore`

## 3. Commit Rules

```bash
git add filename.md
git commit -m "type(scope): short description"
```

- Use present tense
- Keep it short and clear
- Example: `fix(readme): clarify sync steps`

## 4. Push and Open a PR

```bash
git push -u origin your-branch-name
```

Then go to GitHub and click **Compare & pull request**.

- Set base to `main`
- Write a clear title using commit convention
- Add description: what you did and why
- Link the issue: `Closes #ISSUE_NUMBER`

## 5. Getting a Review

- Assign at least one teammate as Reviewer
- Do not merge your own PR
- Wait for approval before merging