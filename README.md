# ClaimBridge — Insurance Claims & Legal Engagement Demo

A complete, responsive, **static** GitHub Pages portfolio demonstration by Wenting Wang.

## What's included

- `index.html` — complete single-page website
- `styles.css` — responsive navy / blue design
- `app.js` — local-only simulated workflow logic

## Features

1. Claim service catalog with eight options: auto/motorcycle, home, catastrophe, condo, renters, business, life, phone protection.
2. First notice of loss intake with basic validation, fictional policy reference, date, time, broad location, description, and simulated notification preference.
3. Auto-specific guidance for safe photos, other-party information, and police reports. No file upload is accepted.
4. Simulated inspection, repair and payment milestones; steps are sequential.
5. Legal workflow: intake triage, matter creation, evidence governance, counsel engagement, settlement, and closure/audit. Simple flags simulate a *recommendation* for specialist review.
6. Client-side-only claim reference, status timeline, and simulated secure inbox. No data is stored or sent to any server.

## Publish via GitHub (no command line)

1. Create a **public** GitHub repository, for example `insurance-claims-demo`.
2. Extract this ZIP. Upload `index.html`, `styles.css`, and `app.js` to the **repository root**, not to a nested folder.
3. Commit files to the `main` branch.
4. In GitHub repository **Settings → Pages**, select **Deploy from a branch**, `main`, `/ (root)`, and Save.
5. Visit `https://YOUR_USERNAME.github.io/insurance-claims-demo/` after deployment.

## Publish using Git Bash

From the directory with the website files:

```bash
git init
git config user.name "Wenting Wang"
git config user.email "YOUR_GITHUB_EMAIL"
git add index.html styles.css app.js README.md
git commit -m "Launch insurance claims legal technology demo"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/insurance-claims-demo.git
git push -u origin main
```

Create the repository online first. Replace `YOUR_USERNAME`, and use your real GitHub commit email or GitHub's noreply email. If an `origin` remote already exists, use `git remote -v` before adding another.

## Customize

- Replace the `mailto:your-email@example.com` link in `index.html` with your professional email, or remove it.
- Replace `ClaimBridge` with a preferred fictional project brand.
- Add links to your LinkedIn, GitHub, or portfolio.
- Update copy to accurately represent your own completed professional work.

## Security and legal limitations

**This is an independent educational prototype, not an official Allstate website.** Allstate and Good Hands® are mentioned only to contextualize the requested insurer journey and are trademarks of their respective owners. No affiliation, endorsement, repair-network access, or warranty is represented.

- Do **not** enter real customer identity information, insurance policy numbers, witness/driver information, claim documents, or any sensitive data.
- No authentication, upload, SMS, email delivery, database, insurer backend, repair network integration, payment initiation, or production AI model exists.
- All input stays in browser memory during the current session. Reloading clears it. It is not encrypted or a secure customer portal.
- Triage is a simple rule-based demonstration and is not a binding insurance, legal, coverage, or claim decision.
- Any real deployment needs secure backend services, access control, encryption, data retention, audit logging, legal and compliance review, privacy controls, consent management, evidence chain of custody, and licensed vendor integrations.
