# Insightis — AI-Powered Decision Intelligence

Marketing landing site for **Insightis**, an AI analytics workspace that connects your data and delivers instant natural-language insights — built by the [Devart](https://www.devart.com/company/) team.

---

## Pages

| Page | File |
|---|---|
| Main Landing | `index.html` |
| AI Chat | `Platform/AI Chat.html` |
| Integrations | `Platform/Integrations.html` |
| Insights Engine | `Platform/Insights Engine.html` |
| Semantic Layer | `Platform/Semantic Layer.html` |
| Reports | `Platform/Reports.html` |
| Memory & Storage | `Platform/Memory & Storage.html` |

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
├── index.html                    # Main landing page
├── README.md
└── Platform/
    ├── AI Chat.html
    ├── Integrations.html
    ├── Insights Engine.html
    ├── Semantic Layer.html
    ├── Reports.html
    └── Memory & Storage.html
```

---

## Deploying

Drag and drop the project folder to **[netlify.com/drop](https://netlify.com/drop)** for an instant shareable link.

> **Note:** File names with spaces may cause 404s on some hosts. If that happens, rename files to use hyphens (e.g. `ai-chat.html`) and update the `linkUrls` objects in each file to match.
