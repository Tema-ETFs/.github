# Tema ETFs — Systems & Automation

This organization holds the scripts, tools, and automations that support Tema ETFs' sales, marketing, and operations teams. The goal is simple: **build things once, document them, and make them repeatable** so knowledge stays with the team, not with any one person.

---

## What lives here

| Area | Examples |
|---|---|
| **CRM tooling** | HubSpot imports, data clean-up and audit scripts, property and workflow utilities, UI extensions |
| **Data pipelines** | Recurring pulls and transforms for fund, distribution, and activity data |
| **Reporting** | Repeatable data pulls behind recurring reports and dashboards |
| **AI skills & actions** | Shared prompts, skills, and agent workflows *(coming soon)* |

---

## How we work

- **One repo per project.** Each tool or process gets its own repository with a clear name (e.g. `hubspot-activity-import`).
- **Every repo has a README** covering what it does, how to run it, required setup, and who owns it.
- **Plays, not one-offs.** Repetitive requests are turned into documented, repeatable processes with clear roles.
- **Private by default.** Project repositories are private to the organization.

---

## Security & compliance

- Two-factor authentication is **required** for all organization members.
- **Never commit secrets.** API keys, tokens, passwords, and credentials belong in environment variables or a secrets manager — not in code, config files, or commit history. Use a `.gitignore` for `.env` files.
- **No client or personal data in repositories.** Sample files should be anonymized.
- All work follows Tema ETFs' Compliance Manual and Code of Ethics.

---

## Getting access

New team members can request access, ask questions, or propose a new tool through the **Systems** request board, or by contacting the Systems team directly.
