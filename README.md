# Raj Patil | Full-Stack Developer
### Python · Django · Frappe · Next.js · Flutter · AI

![Stack](https://img.shields.io/badge/Stack-Python%20%7C%20Django%20%7C%20Next.js-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)

Personal portfolio of Raj Patil, Full-Stack Developer at **Onomatrix Labs Private Limited**. It showcases company work, client websites, and personal backend and AI projects.

[**Explore Live Site →**](https://raj-128.github.io/RajPatil/) · [**Resume (PDF)**](Raj_Patil_Full_Stack_Developer_Resume.pdf)

---

## Tech Stack
| Category | Tools |
| :--- | :--- |
| **Backend** | Python, Django, DRF, Frappe, FastAPI, Node.js |
| **Frontend & Mobile** | JavaScript, TypeScript, React, Next.js, Flutter |
| **Data** | PostgreSQL, MySQL, SQLite, SQL Server |
| **AI** | RAG, LLM APIs, FAISS |
| **Tools** | Git, GitHub, Docker, Postman |

---

## Work

### Flamezo | Onomatrix Labs ([live](https://flamezo.in))
Two-sided local-business platform: outlet discovery, offers, bill payments, table bookings, a cross-outlet loyalty wallet, and a merchant dashboard with AI menu tools. Worked across the Frappe backend, React merchant dashboard, Next.js web app and Flutter app.

### Studio Viana ([live](https://studioviana.work.gd/) · [code](https://github.com/Raj-128/Viana))
Portfolio and ordering site for a 3D and wallpaper studio: instant price estimates, Google sign-in, MFA admin, protected catalogue and print-request flow. Vite, Node.js, SQLite, GSAP.

### Chamomile Media ([code](https://github.com/Raj-128/chamomile-media))
Digital marketing agency website with Netlify Forms enquiries and an optional Google Apps Script backend writing leads to Google Sheets.

### DocuMind ([live](https://documind-zgo1.onrender.com/) · [code](https://github.com/Raj-128/DocuMind))
RAG chatbot built with Django that lets users chat with uploaded documents using context-aware answers.

### Eatify ([live](https://eatify-eyn1.onrender.com/) · [code](https://github.com/Raj-128/Eatify))
Food ordering backend with Django REST Framework: cart, order lifecycle, JWT auth and Cashfree checkout.

### Smart Stick
IoT navigation device for visually impaired users using Python and Raspberry Pi for obstacle detection and voice alerts.

### Complaint Management System
Role-based grievance tracking dashboard in ASP.NET / C# with admin, agent and user workflows.

---

## Site Features
- Full-width responsive layout with dark/light theme toggle
- Scrollspy navigation and scroll reveal animations
- Project modal with live demo and GitHub links
- Resume generated from [resume.html](resume.html)

---

## Local Setup
Static site, no build step:

```bash
git clone https://github.com/Raj-128/RajPatil.git
cd RajPatil
# open index.html in a browser
```

To regenerate the resume PDF after editing `resume.html`:

```bash
msedge --headless=new --no-pdf-header-footer --print-to-pdf="Raj_Patil_Full_Stack_Developer_Resume.pdf" resume.html
```
