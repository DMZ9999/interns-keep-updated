# Setup

## Google Sheet
Import `sheets/companies_template.csv` and keep these columns:
- `company_name`
- `linkedin_url`
- `rss_link`

## n8n
- Import `workflows/linkedin_internship_alerts.json`
- Select your Google Sheet in the Google Sheets node
- Connect your Gmail account (or swap to SMTP)

## Keywords
Open the **Code in JavaScript** node and edit `internKeywords` and `fieldKeywords`.
