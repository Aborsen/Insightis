[README.md](https://github.com/user-attachments/files/26449179/README.md)
# Insightis — AI Analytics Landing Page

Marketing landing site for **Insightis**, an AI-powered analytics workspace built by the Devart team.

## Pages

| Page | File |
|---|---|
| Main Landing | `Main Page 1.html` |
| AI Chat | `Platform/AI Chat 2.html` |
| Integrations | `Platform/Integrations 1.html` |
| Semantic Layer | `Platform/Semantic Lay# Insightis — AI-Powered Decision Intelligence

Marketing landing site for **Insightis**, an AI analytics workspace that connects your data and delivers instant natural-language insights — built by the [Devart](https://devart.com) team.

---

## Pages

| Route | File | Description |
|---|---|---|
| `/` | `index.html` | Main landing page — hero, architecture, testimonials, pricing |
| `/Platform/ai-chat.html` | `Platform/ai-chat.html` | AI Chat feature page |
| `/Platform/integrations.html` | `Platform/integrations.html` | 200+ data source integrations |
| `/Platform/semantic-layer.html` | `Platform/semantic-layer.html` | Semantic Layer feature page |
| `/Platform/reports.html` | `Platform/reports.html` | Reports & sharing feature page |

---

## Tech Stack

| Tool | Usage |
|---|---|
| React 18 | UI components (via CDN, no build step) |
| Babel Standalone | JSX transpilation in-browser |
| Tailwind CSS | Utility-first styling (via CDN) |
| Framer Motion | Animations and transitions |
| Inter / Instrument Sans / JetBrains Mono | Typography (Google Fonts) |

> No bundler, no `node_modules`, no build step — open any `.html` file directly in a browser or serve with any static file server.

---

## Running Locally

```bash
npx http-server . -p 8090
```

Then open `http://localhost:8090`

---

## Project Structure

```
Landing/
├── index.html                  # Main landing page
├── README.md
└── Platform/
    ├── ai-chat.html
    ├── integrations.html
    ├── semantic-layer.html
    └── reports.html
```

---

## Deploying

Drag and drop the project folder to **[netlify.com/drop](https://netlify.com/drop)** for an instant shareable link. `index.html` loads automatically as the root URL.
[README.md](https://github.com/user-attachments/files/26449305/README.md)
er 1.html` |
| Reports | `Platform/Reports 1.html` |

## Tech Stack

- Vanilla HTML/CSS with inline React (via CDN)
- Tailwind CSS (via CDN)
- No build step required

## Running Locally

Serve with any static file server. Using [http-server](https://www.npmjs.com/package/http-server):

```bash
npx http-server . -p 8090
```

Then open `http://localhost:8090/Main%20Page%201.html`

## Deploying

Drag and drop the project folder to [netlify.com/drop](https://netlify.com/drop) for an instant shareable link.

## Structure

```
Landing/
├── Main Page 1.html        # Main landing page
└── Platform/
    ├── AI Chat 2.html
    ├── Integrations 1.html
    ├── Reports 1.html
    └── Semantic Layer 1.html
```
