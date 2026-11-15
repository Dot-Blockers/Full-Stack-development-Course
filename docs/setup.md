# Development Setup

Install a current Node.js LTS release, npm, Git and a code editor. Verify:

```bash
node --version
npm --version
git --version
```

Suggested full-stack project structure:

```text
app/
├── client/src/
├── server/src/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── services/
├── .env.example
├── .gitignore
└── README.md
```

Keep secrets in local environment files and hosting secret settings. Commit only placeholder values in `.env.example`.
