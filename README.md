# 🎉 interns-keep-updated - Get LinkedIn Alerts for Internships

[![Download](https://img.shields.io/badge/Download-v1.0-blue.svg)](https://github.com/DMZ9999/interns-keep-updated/releases)

## 📖 Description
LinkedIn Internship Alerts is a tool that monitors LinkedIn company page posts. It helps you keep updated by sending email alerts when a post includes specific internship and field keywords like "intern," "AI," or their Arabic equivalents. 

## 📁 Contents
- `workflows/linkedin_internship_alerts.json`: Import this file into n8n to set up your alerts.
- `sheets/companies_template.csv`: Use this template to create a Google Sheet for your RSS feeds.
- `docs/`: Find setup instructions, troubleshooting guides, and keyword details.

## 🚀 Getting Started
To get the tool running, follow these steps:

1. **Create a Google Sheet**
   - Open Google Sheets and create a new sheet using the `sheets/companies_template.csv`.

2. **Fill the RSS Link**
   - In your Google Sheet, locate the `rss_link` column and input your RSS feed link. You can use RSSHub or another RSS generator.

3. **Import the Workflow into n8n**
   - Download the `workflows/linkedin_internship_alerts.json` file and import it into n8n.

4. **Set Credentials**
   - Configure your Google Sheets and Gmail credentials within n8n.

5. **Edit Keywords**
   - Look for the **Code** node in the workflow. Customize the keywords to match your interests.

6. **Enable the Workflow**
   - Once everything is set, enable the workflow in n8n to start receiving alerts.

## 📥 Download & Install
To download the latest version of the application, visit the Releases page:

[Download Here](https://github.com/DMZ9999/interns-keep-updated/releases)

## ⚠️ Notes on RSS Stability
Please be aware that public RSSHub instances may sometimes return a status code of 503. For better reliability, consider one of the following options:
- Self-host RSSHub on your own domain or VPS.
- Use a trusted paid RSS provider for consistent service.

## 📝 Additional Features
- **Custom Keywords:** Tailor the keywords based on your area of interest to get relevant internship alerts.
- **Multiple Feeds:** Monitor various companies by using multiple RSS feeds within your Google Sheet.
- **Email Notifications:** Stay updated via email alerts when new postings match your selected criteria.

## 📚 Documentation
For further setup instructions, troubleshooting advice, and examples of keyword usage, check the `docs/` folder included in the project.

## 🛠 System Requirements
- **Operating System:** Windows, macOS, or Linux.
- **Software:** 
  - n8n (latest version recommended)
  - Google Account (for Google Sheets integration)

Feel free to reach out if you have any questions while downloading or setting up the tool. Enjoy monitoring LinkedIn for internship opportunities seamlessly!