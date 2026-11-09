# Kevin Pratama Indrajaya

### Backend Developer · Data Science Student

Application Developer Intern at BCA (Wealth & Treasury) who designs and delivers internal APIs, and part-time developer of a member loyalty system for a 105-outlet barbershop chain. Data Science student at BINUS, graduating 2027.

📍 Jakarta, Indonesia · 📧 kevinkpi012@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/kevin-pratama-indrajaya/) · 🔗 [GitHub](https://github.com/Kiipiiin)

<!-- Download CV: upload the latest CV PDF as assets/img/CV_KevinPratamaIndrajaya.pdf (same file name), then remove these comment markers.
📄 **[Download CV (PDF)](assets/img/CV_KevinPratamaIndrajaya.pdf)**
-->

---

## Experience

### Bank Central Asia (BCA)
**Application Developer Intern – Backend, Wealth & Treasury** · Aug 2026 – Jan 2027

- Designed Swagger (OpenAPI) specs for **7 internal APIs** in wealth and treasury (FX rates, government and treasury bonds, bond coupons, payment status) and registered them on the bank's CI/CD portal.
- Tested each API in the development environment with channel credentials, delivered them to **6 channels** including MyBCA, and moved **4 of them to UAT**.
- Tested investment services moved to **Oracle WebLogic 15c** for success, failure, backend-error and validation-error cases, and set up timeout simulations in Jenkins for testing teams.
- Traced UAT errors in Kibana for **MyBCA investment projects** and worked with backend and API gateway teams to find the cause.

### FI Barbershop
**Part-time Full-Stack Developer** · Feb 2026 – Present

- Built a member loyalty website for a barbershop chain with **105 outlets**: FastAPI and PostgreSQL (Supabase) backend, customer portal, cashier terminal and admin portal. In production since June 2026 (version 2.0 in Oct 2026); public launch planned.
- Synced transaction and outlet data from the **Moka POS API**, and added Google and WhatsApp OTP (Twilio) login with sessions that expire after inactivity.
- Added security checks (request origin checks, rate limits, admin activity logs, Content Security Policy, row-level security, scans with Gitleaks, Semgrep, Bandit and OWASP ZAP) and wrote **306 backend and 99 frontend tests**.
- Built **RFM customer segments** so the admin can send vouchers to specific customer groups.

---

## Featured Projects

### Loan Default Risk Modeling & Segmentation
*Python, XGBoost, Power BI*

- Built an XGBoost model on **30K+ borrower records** to identify high-risk customers (**94% accuracy, 98% precision**), and split defaults into two risk profiles: product-driven and condition-driven.
- Ran an exploratory Thompson Sampling (Bayesian) simulation for medium-risk borrowers, projecting default reductions of about **12% (product risk) and 21% (condition risk)** under assumed treatment effects.
- Built a Power BI dashboard that explains the model with SHAP values.

### Shopee Negative Reviews – Topic Modelling
*Python, IndoBERT, K-Means, NLP*

- Turned **30K+ Indonesian Shopee reviews** into IndoBERT embeddings and grouped them with K-Means into three stable complaint themes (shipping, UX, technical).
- Tracked topic drift across app versions 3.40–3.62: **UX issues grew fastest**, with spikes in versions 3.59–3.61, which points to prioritizing UX over operational fixes.

### Sales & Customer Analytics Dashboard
*Power BI*

- Analyzed **48K e-commerce transactions** and found a revenue breakout after April, the Website as the dominant sales channel, and a country-level refund anomaly (Brazil's high refund rate).

### Crowd Counting – Computer Vision
*Python, deep learning*

- Built a crowd counting model trained on density maps to handle uneven crowd density across images.
- Reached an **MAE of 29** on 190 test images; the pretrained variant performed best on highly crowded scenes.

---

## Tech Stack

| Category | Tools / Skills |
|----------|----------------|
| Languages | Python, SQL (PostgreSQL), JavaScript, HTML/CSS |
| Backend & APIs | FastAPI, REST APIs, Swagger/OpenAPI, JWT, Google OAuth, Twilio (WhatsApp OTP) |
| Data & ML | PyTorch, Scikit-learn, XGBoost, IndoBERT, K-Means, SHAP, text mining, deep learning |
| Visualization & apps | Power BI, Streamlit |
| Tools & platforms | Git/GitHub, GitLab, Jenkins, Kibana, Oracle WebLogic, Supabase, Railway, Vercel |
| Testing & security | pytest, SIT/UAT, Content Security Policy, OWASP ZAP, Semgrep |
| Also | Kafka and message queues (basics), AI-assisted development (Claude Code) with code review |

---

## Education & Certifications

**Universitas Bina Nusantara (BINUS)** – Data Science · Aug 2023 – 2027 (expected)

- **Certifications:** Data Classification Using IBM Granite (IBM); Deep Learning A-Z and Business Data Science (Udemy); Practical Machine Learning (Digital Talent Scholarship)
- **Languages:** Indonesian (native); English (TOEFL ITP 623/677, professional working proficiency); Mandarin Chinese (HSK 2)
