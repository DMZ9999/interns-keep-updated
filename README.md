# LinkedIn Internship Alerts (n8n)

Monitor LinkedIn company page posts via RSS feeds and receive email alerts when a post matches:
- Internship keywords (intern/internship/تدريب…)
- Field keywords (AI/ML/Data + Arabic variants)

## Contents
- `workflows/linkedin_internship_alerts.json` — import into n8n
- `sheets/companies_template.csv` — Google Sheets template
- `docs/` — setup + troubleshooting + keywords

## Quick start
1. Create a Google Sheet using `sheets/companies_template.csv`
2. Fill the `rss_link` column (RSSHub or another RSS generator)
3. Import the workflow JSON into n8n
4. Set Google Sheets + Gmail credentials
5. Edit keywords in the **Code** node
6. Enable the workflow

## Notes on RSS stability
Public/community RSSHub instances often return 503. For reliability:
- self-host RSSHub on your own domain/VPS, or
- use a stable paid RSS “page-to-RSS” provider.
