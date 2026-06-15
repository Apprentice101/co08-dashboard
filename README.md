# CO-08 Voting Procedures Dashboard

CO-08 (Gabe Evans R-inc vs Rutinel/Bird D primary June 30, David Wood L)

Built from `voting-dashboards-source` repo on 2026-06-12.

## Files
- `index.html` — entry point
- `snapshot.json` — district data (data layer)
- `assets/` — bundled JS/CSS

## Deploy to GitHub Pages

```bash
# In Apprentice101/co08-dashboard repo:
git add .
git commit -m "Deploy CO-08 dashboard"
git push -u origin main
```

Enable GitHub Pages from main branch root in repo settings.

## QA status (2026-06-12)

All rules: `needsReview: true, confidence: "unconfirmed"` — verify against state SOS and county election offices before publish.

All sources tagged with sourceType (`official-state`, `official-county`, `statutory`, `secondary`, `news`) per project standard.

## Source tiers covered

- Tier 1 (official state): State SOS / Division of Elections
- Tier 1 (official county): County election office(s)
- Tier 2 (statutory): State revised statutes / session law
- Tier 3 (nonpartisan journalism): Statewide outlets, Ballotpedia, district-specific reporting

See snapshot.json for full source roster.
