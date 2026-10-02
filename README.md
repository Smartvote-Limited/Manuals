# Smartvote Limited Manuals

Central repository for manuals, guides, procedures, and documentation used across Smartvote Limited.

This repository is intentionally not limited to software. It may contain documentation for systems, products, hardware, internal procedures, training materials, and other operational resources.

## Structure

- `products/` — Product-specific manuals and user guides
- `systems/` — System and platform documentation
- `hardware/` — Hardware setup, installation, and maintenance guides
- `procedures/` — Internal procedures and operational instructions
- `training/` — Training and onboarding materials
- `templates/` — Reusable documentation templates
- `assets/` — Shared images, diagrams, screenshots, and other assets

## Documentation Guidelines

1. Create one folder per product, system, device, or procedure.
2. Use Markdown (`.md`) as the primary documentation format where practical.
3. Store related screenshots and diagrams close to the manual or under `assets/`.
4. Use clear step-by-step instructions for operational procedures.
5. Keep technical implementation documentation in the relevant source-code repository when it is only useful to developers.
6. Keep customer-facing, operator-facing, and organization-wide manuals in this repository.

## Naming

Use lowercase kebab-case for folders and files where practical.

Example:

```text
products/
└── inventory-management/
    ├── README.md
    ├── getting-started.md
    ├── daily-operations.md
    ├── troubleshooting.md
    └── images/
```

## Manual Template

Start new manuals from [templates/manual-template.md](templates/manual-template.md).
