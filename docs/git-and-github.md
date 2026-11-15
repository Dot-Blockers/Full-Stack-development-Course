# Git & GitHub Workflow

Branch names: `feature/name`, `fix/name`, `docs/name`, `test/name`.

```bash
git switch -c feature/add-task-filter
git add .
git commit -m "feat: add task status filter"
git push -u origin feature/add-task-filter
```

Open a pull request with purpose, implementation notes, test commands and screenshots when relevant. Never commit `.env`, credentials, private data or `node_modules`.
