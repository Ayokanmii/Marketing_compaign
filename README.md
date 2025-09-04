📩 AI-Powered Marketing Campaign Automation

A fully automated AI-driven marketing campaign workflow built with n8n, designed to help e-commerce businesses like ShopWise send personalized customer emails at scale.

This project integrates CRM data, AI-generated email content, automated segmentation, and Gmail delivery, ensuring the right customer gets the right message at the right time.

🚀 Features

Daily Automated Campaigns – triggers every morning at 8AM.

Customer Segmentation – classifies users as high-value or inactive based on purchase history.

AI-Powered Email Generation – personalized subject lines, offers, and calls-to-action.

Seamless Delivery via Gmail – sends emails directly to customers.

Campaign Logging – records campaign details into Google Sheets for tracking & analysis.

End-to-End Automation – no manual intervention required.

🛠️ Tech Stack

n8n – workflow automation engine.

OpenAI API – for AI-powered personalized email content.

Google Sheets – stores customer data & campaign logs.

Gmail API – sends customer emails.

📂 Workflow Overview

The workflow consists of the following nodes:

1. Schedule Trigger – Runs daily at a fixed time.


2. Fetch CRM Data – Retrieves customer info from Google Sheets.


3. Segment Customers – Groups customers into active/inactive segments.


4. Generate Email Content – AI creates personalized messages.


5. Parse Email Output – Structures email subject + body.


6. Send Campaign Email – Emails delivered via Gmail.


7. Log Campaign – Updates Google Sheets with campaign details.


📊 Example Campaign Flow

A customer with no purchases in 30+ days → receives a “We miss you” reactivation email.

A repeat buyer with high-value purchases → receives a “VIP exclusive discount” email.

Each email is AI-personalized to include the customer’s name, purchase history insights, and relevant offers.


🎯 Impact

Increased engagement through personalized outreach.

Reduced churn by reactivating inactive customers.

Streamlined workflow – from data to email to reporting.

Scalable solution for growing e-commerce platforms.
👨‍💻 Author

Olatunji Ayokanmi Damilola
Frontend & Full-Stack Developer | Software Tester | AI Integrator

📩 Email: olatunjiayokanmii@gmail.com
🌐 Portfolio: ayokanmi-portfolio.netlify.app

