# Insightis — AI-Powered Decision Intelligence

Marketing landing site for **Insightis**, an AI analytics workspace that connects your data and delivers instant natural-language insights — built by the [Devart](https://devart.com) team.

---

## Pages

| Page | File |
|---|---|
| Main Landing | `index.html` |
| AI Chat | `Platform/AI Chat.html` |
| Integrations | `Platform/Integrations.html` |
| Semantic Layer | `Platform/Semantic Layer.html` |
| Reports | `Platform/Reports.html` |

---

## Tech Stack

| Tool | Usage |
|---|---|
| React 18 | UI components (via CDN) |
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
├── index.html                   # Main landing page
├── README.md
└── Platform/
    ├── AI Chat.html
    ├── Integrations.html
    ├── Semantic Layer.html
    └── Reports.html
```

---

## Deploying

Drag and drop the project folder to **[netlify.com/drop](https://netlify.com/drop)** for an instant shareable link.

> **Note:** File names with spaces (`AI Chat.html`, `Semantic Layer.html`) may cause 404s on some hosts. If that happens, rename them to `ai-chat.html` and `semantic-layer.html` — the navigation links will need to be updated to match.
