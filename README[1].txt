
📘 FlareCast v1.4 – README

Welcome to FlareCast – a privacy-first flare-up prediction and symptom tracking app for chronic illness and autoimmune disease management.

✅ Key Features:
- Anonymous EIL ID tracking
- Daily symptom log with flare score
- Baseline day intake form
- Flare report PDF generation
- Terms of Use & friendly error handling
- Mobile-optimized interface
- Weekly log backup (manual script ready)
- Anonymous usage analytics logging

📂 File Structure:
- app.py – Flask application
- templates/ – HTML pages
- logs/ – User symptom logs, usage analytics, PDF reports
- version.txt – Current version details

🚀 Deployment Instructions:
1. Upload files to your Python-capable web host (e.g., Hostinger Premium with SSH).
2. SSH into your server and run:
   pip install -r requirements.txt
   flask run --host=0.0.0.0 --port=5000
3. Access your app via IP or domain.
4. Bookmark: /baseline and /report for intake and reports.

