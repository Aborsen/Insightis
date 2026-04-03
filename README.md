# Insightis — AI-Powered Decision Intelligence

Marketing landing site for **Insightis**, an AI analytics workspace that connects your data and delivers instant natural-language insights — built by the [Devart](https://www.devart.com/company/) team.

---

## Pages

### Main
| Page | File |
|---|---|
| Landing | `index.html` |

### Platform
| Page | File |
|---|---|
| AI Chat | `Platform/AI Chat.html` |
| Integrations | `Platform/Integrations.html` |
| Insights Engine | `Platform/Insights Engine.html` |
| Semantic Layer | `Platform/Semantic Layer.html` |
| Reports | `Platform/Reports.html` |
| Memory & Storage *(coming soon)* | `Platform/Memory & Storage.html` |

### Solutions
| Page | File |
|---|---|
| RevOps & BizOps | `Solutions/RevOps BizOps.html` |
| Founders & CEOs | `Solutions/Founders CEOs.html` |
| Marketing Teams | `Solutions/Marketing Teams.html` |
| Product Teams | `Solutions/Product Teams.html` |
| Data & Analytics Teams | `Solutions/Data Analytics Teams.html` |
| Operations & Finance | `Solutions/Operations Finance.html` |

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
├── index.html
├── README.md
├── Platform/
│   ├── AI Chat.html
│   ├── Integrations.html
│   ├── Insights Engine.html
│   ├── Semantic Layer.html
│   ├── Reports.html
│   └── Memory & Storage.html
└── Solutions/
    ├── RevOps BizOps.html
    ├── Founders CEOs.html
    ├── Marketing Teams.html
    ├── Product Teams.html
    ├── Data Analytics Teams.html
    └── Operations Finance.html
```

---

## Deploying

Drag and drop the project folder to **[netlify.com/drop](https://netlify.com/drop)** for an instant shareable link.

> **Note:** File names with spaces may cause 404s on some hosts. If that happens, rename files to use hyphens (e.g. `revops-bizops.html`) and update the `linkUrls` objects in each file to match.
