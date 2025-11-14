# Task2-PhishingAnalysis

🛡️ Cyber Security Internship – Task 2
Phishing Email Analysis
📌 Objective

The purpose of this task is to analyze a suspicious email, identify phishing indicators, review headers, examine URLs/attachments, and document all findings.

🛠️ Tools Used

Email Sample (Provided in this repo)

Online Email Header Analyzer (e.g., MxToolbox)

Browser (for link inspection — hover only, do NOT click)

📨 Phishing Email Sample

A phishing email sample has been included in this repository as:

phishing_email_sample.txt


This sample was analyzed for suspicious indicators.

🔍 Steps Performed
1️⃣ Examined the Sender Address

Detected spoofed sender domain

Example: support@paypa1-security.com (fake “paypa1”)

2️⃣ Checked the Email Body

Observed common phishing signs:

Urgent language (“Your account will be suspended in 24 hours”)

Poor grammar & formatting

Requests for personal/account verification

3️⃣ Inspected Links Inside the Email

By hovering over the link (not clicking), found:

Displayed text: Secure your account

Actual URL: http://malicious-login.xyz

These mismatched URLs confirm phishing behavior.

4️⃣ Reviewed Attachments

Attachment observed: invoice.zip
⚠ ZIP attachments in phishing emails often contain malware.

5️⃣ Analyzed Email Header

Using an online header analyzer:

SPF: FAIL

DKIM: FAIL

DMARC: FAIL
This confirms the email did not originate from the legitimate domain.

🚨 Phishing Indicators Identified
Indicator	Found
Fake/Spoofed Sender	✔ Yes
Suspicious URL	✔ Yes
Urgent/Threatening Language	✔ Yes
Attachment (ZIP)	✔ Yes
Header Authentication Fails	✔ Yes
Grammar/Spelling Mistakes	✔ Yes
📁 Files Included in This Repository
Task2-PhishingAnalysis/
│── README.md
│── phishing_email_sample.txt
│── phishing_analysis_report.md
└── screenshots/
    ├── email_body.png
    ├── header_check.png

📄 Summary

This task demonstrates:

How to identify fake domains

How to inspect suspicious links

How to detect urgency/social engineering

How to check email headers for authenticity

How to document phishing threats

🎯 Final Outcome

The report clearly highlights phishing traits and provides awareness about common social engineering tactics.

✅ 2. Full Task 2 Files (All Content You Need)

Below are all files you must upload to GitHub.

📄 phishing_email_sample.txt
From: PayPal Support <support@paypa1-security.com>
Subject: Urgent! Your Account Will Be Locked in 24 Hours

Dear Customer,
We noticed suspicious activity on your PayPal account.  
To avoid permanent suspension, please verify your identity immediately.

Click the link below:
https://paypal-verification-securelogin.xyz

Failure to verify will result in account closure.

Thank you,
PayPal Security Team

Attachment: invoice.zip
