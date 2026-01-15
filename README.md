# 🧭 RETRIVO — Smart Lost & Found System

**RETRIVO** is a calm, privacy-aware web application designed to help people **report, discover, and recover lost items** in shared spaces such as campuses, offices, and communities.

Unlike traditional lost-and-found systems, RETRIVO focuses on **verified recovery**, ensuring trust, transparency, and closure.

🔗 **Live Demo:** 👉 [https://aanshigahlot1.github.io/RETRIVO/](https://aanshigahlot1.github.io/RETRIVO/)

---

## 📌 Problem Statement

In shared environments, losing a personal item often leads to:
- **Panic and confusion** due to lack of a central system.
- **Scattered messages** across various WhatsApp or Telegram groups.
- **Physical notice boards** that are easily ignored or outdated.
- **No reliable verification** when an item is claimed.

Most existing systems only list items and fail to **close the recovery loop** effectively.

---

## 💡 Solution Overview

RETRIVO solves this by providing:
- **Structured reporting** for lost and found items.
- **Smart matching** based on item name and location.
- **Email-based ownership confirmation** to prevent false claims.
- **Automatic removal** of recovered items to keep the feed clean.
- **Recovery history** for long-term transparency.

All wrapped in a **minimal, calm UI** designed to reduce stress for the user.

---

## ⚙️ How RETRIVO Works

1. **Report Lost Item:** Users submit item details (name, location, date, contact info, image).
2. **Report Found Item:** Users who find an item submit matching details.
3. **Smart Matching:** The system checks for matches using item name and location logic.
4. **Email Confirmation:** If a match is found, an email is sent to the lost-item owner with a confirmation link.
5. **Verified Recovery:** On confirmation, the finder’s contact details are revealed, and the item is moved to the recovery history.
---
## 📂 Project Structure

```text
RETRIVO/
├── index.html       # Home page
├── lost.html        # Report lost items
├── found.html       # Report found items
├── items.html       # Browse active lost & found items
├── history.html     # Recovered items history
├── confirm.html     # Recovery confirmation & contact sharing
├── contact.html     # Contact page (frontend-only)
├── style.css        # Global styling and UI theme
└── README.md        # Project documentation
```
---

## 🧪 Key Features

* **Structured Reporting:** Intuitive forms for reporting items quickly.
* **Image Upload Support:** Powered by **Cloudinary** for high-quality hosting.
* **Smart Logic:** Matching algorithms based on item descriptors and location tags.
* **Email Verification:** Secure ownership verification via **EmailJS**.
* **Privacy First:** Contact details remain hidden until ownership is confirmed.
* **Auto-Cleanup:** Listings are automatically archived once recovered.
* **History Archive:** A dedicated log for all successfully returned items.

---

## 🛠 Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6)
* **Database:** Firebase Realtime Database
* **Image Hosting:** Cloudinary (Unsigned Uploads)
* **Email Service:** EmailJS
* **Hosting:** GitHub Pages

---

## 🔒 Privacy & Safety Design

* Contact details are hidden until ownership is confirmed.
* Finder information is shared only after system verification.
* No unnecessary data collection or exposed credentials.
* Serverless architecture reduces traditional security risks.
---
## 🌐 Open in Browser & Deployment

### 🔹 Run Locally

To run the project on your local machine, start a local server using Python:

```bash
python -m http.server 5500
```
---

## 📈 Future Enhancements

* **AI Matching:** Implementing AI-based image similarity matching.
* **Multi-Factor Auth:** Adding OTP verification for high-value items.
* **Admin Dashboard:** Tools for moderation and community analytics.
* **PWA Support:** Turning the app into a mobile-friendly Progressive Web App.
* **Framework Migration:** Moving to React.js for better scalability.

---

## 👩‍💻 Author

**Aanshi Gahlot** B.Tech Computer Science & Engineering  
Self-initiated Full-Stack Web Project  
**GitHub:** [@aanshigahlot1](https://github.com/aanshigahlot1)

---
---

### 🤝 Let's Connect!

If you like this project, feel free to **star ⭐ this repository** and follow my journey! I’m always open to feedback, collaborations, and discussions about web development and AI.

* **Project Name:** RETRIVO
* **Version:** 1.0.0
* **Status:** Active Development

**Thanks for visiting!** 🚀


