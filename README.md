# RunQuest Legal

Public legal pages for RunQuest.

Canonical site:

https://runrpg.astralogy.org/

## Pages

- Privacy Policy: https://runrpg.astralogy.org/
- Terms of Use: https://runrpg.astralogy.org/terms/
- Support: https://runrpg.astralogy.org/support/

## Deployment

This repository is intended to be published with GitHub Pages from the `main` branch root.

The `CNAME` file sets the custom domain:

```text
runrpg.astralogy.org
```

Cloudflare DNS should contain:

```text
Type: CNAME
Name: runrpg
Target: joojoomie.github.io
Proxy status: DNS only
TTL: Auto
```

Keep Cloudflare proxy disabled while GitHub Pages validates the custom domain and provisions HTTPS. After HTTPS is active and stable, proxying can be reviewed separately.

## Editing Rules

- Keep the pages bilingual in Chinese and English.
- Keep Privacy, Terms, and Support links in sync across pages.
- Do not claim medical diagnosis, treatment, or training prescription.
- Do not claim RunQuest sells power, HealthKit-data ads, or paid random equipment advantages.
- Update the effective date when the substance of a legal page changes.

This repository is not a substitute for formal legal review.
