# Smartvote Limited Manuals

[![CI/CD](https://github.com/Smartvote-Limited/Manuals/actions/workflows/pages.yml/badge.svg)](https://github.com/Smartvote-Limited/Manuals/actions/workflows/pages.yml)

Central repository for manuals and documentation used across Smartvote Limited.

The documentation website is built from Markdown files under `docs/` using MkDocs Material and deployed automatically with GitHub Actions.

## Structure

```text
Manuals/
├── README.md
├── mkdocs.yml
├── requirements.txt
├── docs/
│   ├── index.md
│   ├── templates/
│   │   └── manual-template.md
│   ├── stylesheets/
│   │   └── extra.css
│   └── <manual-name>/
│       └── index.md
└── .github/
    └── workflows/
        └── pages.yml
```

Create one folder under `docs/` for each subject, product, project, or manual. There is no required category such as software, hardware, or systems.

## Documentation Guidelines

1. Use Markdown (`.md`) as the primary documentation format.
2. Name folders and files clearly, preferably using lowercase kebab-case.
3. Keep screenshots and related assets close to the manual that uses them.
4. Use clear step-by-step instructions for operational procedures.
5. Keep developer-only implementation documentation in the relevant source-code repository.
6. Add new published manuals to the navigation in `mkdocs.yml`.

## Manual Template

Start new manuals from [`docs/templates/manual-template.md`](docs/templates/manual-template.md).

## Documentation Website

https://smartvote-limited.github.io/Manuals/
