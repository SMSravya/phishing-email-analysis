# 📧 Phishing Email Analysis Report

## 👤 Submitted by
**Name**: S M Sravya  
**Internship**: Cybersecurity Internship  
**Task**: Task 2 – Analyze a Phishing Email Sample  

---

## 🖼️ Screenshot of Email

![Phishing Email](./screenshots/phishing_email.png)

---

## 🔍 Email Overview

- **From**: `service.epaypal@outlook.com` (appears as `service@intl.paypal.com`)
- **Subject**: "Response required"
- **Date**: January 29, 2016
- **Pretending to be**: PayPal
- **Goal**: Trick the user into clicking a fake link and entering PayPal credentials

---

## 🛠️ Analysis of Phishing Indicators

### 🚩 1. Suspicious Sender Email
The actual email is from `service.epaypal@outlook.com`, which is not a legitimate PayPal domain. The name appears as `service@intl.paypal.com` to mislead the recipient.

### 🌐 2. Misleading Links
The email includes a link labeled “Resolution Center,” which may redirect to a fake PayPal login page intended to steal credentials.

### 🔐 3. Urgent Language
The subject line and message content emphasize urgency: “Your account is temporarily limited.” Such language pressures users into acting quickly.

### 👤 4. Generic Greeting
The email begins with “Dear Customer” instead of using the recipient’s actual name. PayPal typically uses personalized greetings.

### 🧠 5. Social Engineering Techniques
The email builds fake credibility and trust, offering help and using phrases like “We’re always here to help” to seem legitimate.

---

## ✅ Summary of Red Flags

| Red Flag                | Description                                               |
|-------------------------|-----------------------------------------------------------|
| 🚨 Urgency              | Subject line and body emphasize account limitations       |
| 📧 Spoofed Address      | `@outlook.com` sender pretending to be PayPal             |
| 🔗 Misleading Links     | Anchor text disguises destination URL                     |
| 👤 Generic Greeting     | “Dear Customer” used instead of real user’s name          |
| 🧠 Social Engineering   | Fear tactics and fake support tone to appear trustworthy  |

---

## 📌 Conclusion

This email is a **classic phishing attempt**. It leverages spoofed sender identity, scare tactics, misleading links, and social engineering to trick users into revealing personal information. These are common phishing traits users must learn to recognize and report.

---

## 🛑 Security Tip

Always:
- Double-check the sender’s full email address
- Hover over links to verify their destination
- Avoid clicking on links from unknown or suspicious emails
- Report phishing emails to your mail provider or security team

---

## 📁 Repo Structure

phishing-email-analysis/
│
├── screenshots/
│   └── phishing_email.png
├── Phishing_Email_Analysis_Report.pdf
├── README.md
