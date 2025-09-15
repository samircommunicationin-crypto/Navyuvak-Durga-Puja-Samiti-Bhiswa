# Centralized Puja Samiti Website Setup

## 1️⃣ Google Apps Script
- Create a Google Apps Script project.
- Connect it to Google Sheets (Donation Data, Members, About).
- Create REST APIs:
    - GET /donations
    - GET /members
    - GET /about
    - POST /admin/add-donation
    - POST /admin/edit-members
    - POST /admin/update-about

## 2️⃣ Deployment
- Replace YOUR_APPS_SCRIPT_URL in HTML files with deployed Apps Script URL.
- Host entire folder on GitHub Pages.

