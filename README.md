# Insightis — AI-Powered Decision Intelligence

Marketing landing site for **Insightis**, an AI analytics workspace that connects your data and delivers instant natural-language insights — built by the [Devart](https://www.devart.com/company/) team.

---

## Pages

### Main
| Page | File |
|---|---|
| Landing | `index.html` |
| Pricing | `Pricing.html` |

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

### Resources
| Page | File |
|---|---|
| Documentation | `Resources/Documentation.html` |
| Blog | `Resources/Blog.html` |
| Support Center| `Resources/Contact Support.html` |
| AI Connect | `Resources/AI Connect.html` |
| Video Tutorials | https://www.youtube.com/@InsightisAI |

### Company
| Page | File |
|---|---|
| About Insightis | `Company/About Insightis.html` |
| Contacts | `Company/Contacts.html` |
| Success Stories | `Company/Success Stories.html` |
| Press & Media | `Company/Press Media.html` |

---

## Navigation

The nav bar has four top-level items: **Platform**, **Solutions**, and **Resources** (each with a dropdown), and **Pricing** (direct link). Company pages are linked from the footer only.

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
├── Pricing.html
├── README.md
├── Platform/
│   ├── AI Chat.html
│   ├── Integrations.html
│   ├── Insights Engine.html
│   ├── Semantic Layer.html
│   ├── Reports.html
│   └── Memory & Storage.html
├── Solutions/
│   ├── RevOps BizOps.html
│   ├── Founders CEOs.html
│   ├── Marketing Teams.html
│   ├── Product Teams.html
│   ├── Data Analytics Teams.html
│   └── Operations Finance.html
├── Resources/
│   ├── Documentation.html
│   ├── Blog.html
│   ├── Contact Support.html
│   └── AI Connect.html
└── Company/
    ├── About Insightis.html
    ├── Contacts.html
    ├── Success Stories.html
    └── Press Media.html
```

---

## Deploying

Drag and drop the project folder to **[netlify.com/drop](https://netlify.com/drop)** for an instant shareable link.

> **Note:** File names with spaces may cause 404s on some hosts. If that happens, rename files to use hyphens (e.g. `revops-bizops.html`) and update the `linkUrls` objects in each file to match.
