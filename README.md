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
| **Tools** | Git, GitHub, Docker, Celery, Redis, Postman |

---

## Work

### Studio Viana — live client site ([live](https://studioviana.work.gd/) · [code](https://github.com/Raj-128/Viana))
Portfolio and ordering site for a 3D and wallpaper studio: 3D wallpaper corridor, instant price estimates, Google sign-in, MFA admin, protected catalogue and print-request flow. Vite, Node.js, SQLite, GSAP.

### Chamomile Media — in progress ([code](https://github.com/Raj-128/chamomile-media))
Digital marketing agency website: 3D gallery tunnel, client carousel, services and work pages, and an enquiry flow writing leads to Google Sheets.

### DocuMind ([live demo](https://documind-zgo1.onrender.com/) · [code](https://github.com/Raj-128/DocuMind))
RAG chatbot: upload a PDF, ask questions, get context-aware answers, summaries and key points. Django, FAISS, LangChain, Groq.

### Eatify ([live demo](https://eatify-eyn1.onrender.com/) · [code](https://github.com/Raj-128/Eatify))
Food ordering platform: menu search, cart, wishlist, addresses, order history and Cashfree payments. Django, SQLite.

### RajMind ([live demo](https://rajmind.onrender.com) · [code](https://github.com/Raj-128/RajMind))
Multi-tenant AI knowledge assistant: workspaces with RBAC, background document processing, and answers cited to the source. Django, PostgreSQL, Celery, Docker.

### Open source: dlt-error-codes ([npm](https://www.npmjs.com/package/dlt-error-codes) · [code](https://github.com/Raj-128/dlt-error-codes))
Plain-English explanations and fixes for Indian DLT SMS error codes, each citing its source. Zero dependencies, tested in CI.

---

## Site Features
- Full-width responsive layout with dark/light theme toggle
- Opening screen: name over a starfield and 3D globe ([cobe](https://github.com/shuding/cobe)); scrolling spins the globe to Surat, then the intro slides up over it like a new page
- Word-by-word hero title, directional and staggered scroll reveals, portrait parallax
- Minimal header (name + theme toggle) on the opening screen; full sticky navbar once the intro arrives
- Scroll progress bar, 3D tilt on project cards
- Ring-and-dot cursor drawn as the native OS cursor (no lag, never splits); WebGL globe pauses when off screen
- Respects `prefers-reduced-motion`
- Scrollspy navigation
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
