# Purrfect

Collection of tools for extracting and visualising codebase metadata.

## Recommended Reading

Agents SHOULD scan these files for definitions and resource locations when faced with uncertainty or ambiguity that may result from missing resources.

- `_guide.md` — this file: system overview, layout, records, and operating instructions.
- `_records/project.art` — the project record.
- `_records/repository.art` — the repository record.
- `_records/namespace.art` — the namespace record.

## Repository Layout

```
_guide.md           — this file
_records/           — project and repository records
```

## Records Management

Records are co-located with the resources they describe in `_records/` directories:

- **Project:** `_records/project.art`
- **Repository:** `_records/repository.art`
- **Namespace:** `_records/namespace.art`

## Operating Instructions

### Operating Instructions: Setting Up

**Instructions:**

Run from the repository root (monorepo):

```bash
npm ci # to install dependencies.
```

### Operating Instructions: Verifying Completion

**Instructions:**

Run from the repository root (monorepo):

```bash
npm run ci # lint, build and test
```