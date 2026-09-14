# Shub202 ASCII / Terminal GitHub Profile

This version is intentionally based on the clean structure of the reference screenshot:

- large ASCII-style visual at the top
- compact `about`, `stack`, `projects`, `stats`, and `activity` sections
- text-first project presentation
- terminal/editorial typography
- no photo
- no large decorative section panels

## Important exclusions

This README does **not** use these labels or banner panels:

- `EXPERIENCE / IMPACT`
- `PROJECTS / SHIPPED`
- `ACHIEVEMENTS / CREDENTIALS`

Experience, projects, and achievements are presented as normal compact sections instead.

## Structure

```text
Shub202/
├── README.md
├── SETUP.md
├── ├── art/
│   ├── ascii-hero.svg
│   └── divider.svg
├── profile/
│   └── metrics.svg
└── .github/
    └── workflows/
        ├── snake.yml
        └── metrics.yml
```

## Push

Run from the ROOT folder:

```powershell
git init
git add .
git commit -m "Create ASCII terminal-style GitHub profile"
git branch -M main
git remote add origin https://github.com/Shub202/Shub202.git
git push -u origin main --force
```

Do not run `git init` inside `.github`.

## Actions

After the push:

```text
GitHub → Shub202/Shub202 → Actions
```

Run:

- Generate Contribution Snake
- Generate GitHub Metrics

The workflows also contain a scheduled trigger for later automatic runs.

## Permissions

If an Action cannot write generated files:

```text
Settings → Actions → General → Workflow permissions
```

Select:

```text
Read and write permissions
```

Then rerun the workflow.

## Source of profile claims

Professional content is based on the supplied resume. Keep the README updated if your projects, experience, or skills change.
