# 🧭 RETRIVO — Smart Lost & Found System

**RETRIVO** is a calm, privacy-aware web application designed to help people **report, discover, and recover lost items** in shared spaces such as campuses, offices, and communities.

Unlike traditional lost-and-found systems, RETRIVO focuses on **verified recovery**, ensuring trust, transparency, and closure.

🔗 **Live Demo:**  
👉 https://aanshigahlot1.github.io/RETRIVO/

---

## 📌 Problem Statement

In shared environments, losing a personal item often leads to:
- Panic and confusion
- Scattered messages across WhatsApp groups
- Physical notice boards that go unnoticed
- No reliable verification when an item is returned

Most existing systems only list items and fail to **close the recovery loop**.

---

## 💡 Solution Overview

RETRIVO solves this by providing:

- Structured reporting for lost and found items
- Smart matching based on item name and location
- Email-based ownership confirmation
- Automatic removal of recovered items
- A recovery history for transparency

All wrapped in a **minimal, calm UI** designed to reduce cognitive load.

---

## ⚙️ How RETRIVO Works

1. **Report Lost Item**  
   Users submit item details (name, location, date, contact info, image).

2. **Report Found Item**  
   Users who find an item submit matching details.

3. **Smart Matching**  
   The system checks for matches using item name and location.

4. **Email Confirmation**  
   If a match is found, an email is sent to the lost-item owner with a confirmation link.

5. **Verified Recovery**  
   On confirmation:
   - Finder’s contact details are revealed
   - Item is removed from active listings
   - Record is archived in recovery history

---

## 🔒 Privacy & Safety Design

- Contact details are hidden until ownership is confirmed
- Finder information is shared only after verification
- No unnecessary data collection
- No admin backdoors or exposed credentials
- Serverless architecture reduces security risk

This ensures **trust, privacy, and controlled data sharing**.

---

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6)
- **Database:** Firebase Realtime Database
- **Image Hosting:** Cloudinary (unsigned uploads)
- **Email Service:** EmailJS
- **Hosting:** GitHub Pages

---

## 📂 Project Structure

