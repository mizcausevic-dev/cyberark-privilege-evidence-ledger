# cyberark-privilege-evidence-ledger

Board-readable Kinetic Gain proof repo for **CyberArk** platform and company signal coverage.

## Product thesis

Privileged access creates board-visible exposure when safe ownership, session risk, rotation evidence, and exceptions are not reviewable.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** CISOs, PAM owners, identity governance teams, and audit leaders
- **Signal domain:** IAM / Privileged Access
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product maps privileged accounts, safes, session posture, rotation gaps, and exception ownership into one evidence ledger.
- **Value architecture:** Leaders can prioritize high-risk privilege cleanup, reduce audit scramble, and justify PAM investment with concrete exposure data.

## What this repo proves

- **Normalize:** messy CyberArk operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: CyberArk safes, privileged accounts, session logs, credential rotation, ownership maps, and exception tickets.

This is synthetic proof only. It does not connect to live CyberArk tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- CyberArk
- PAM
- privileged access
- session risk
- access evidence
