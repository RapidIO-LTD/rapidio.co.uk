# Rapid IO LTD — Official Company Website

Institutional website for **Rapid IO LTD** (`rapidio.co.uk`), engineered for GitHub Pages static hosting.

Positioned for:
- **Capital Markets & Financial Institutions**: Tier-1 investment banks, quantitative funds, and trading syndicates seeking high-throughput distributed systems (.NET / Microsoft Orleans / low-latency architectures).
- **Frontier AI & Accelerator Programs**: Anthropic AI Startup Program evaluation, showcasing applied agentic AI, enterprise RAG, and Claude-powered workflows.

---

## Repository Structure

```
├── CNAME           # Custom domain mapping (rapidio.co.uk)
├── index.html      # Production-grade single-page institutional website
├── favicon.svg     # Rapid IO vector logo / monogram favicon
├── robots.txt      # Search engine crawl instructions
├── sitemap.xml     # SEO sitemap
└── README.md       # Deployment & DNS configuration guide
```

---

## GitHub Pages & DNS Configuration Guide

### 1. Enable GitHub Pages
1. Push this repository to GitHub under your account / organization.
2. Go to **Settings** > **Pages** in the GitHub repository.
3. Under **Build and deployment**:
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`
4. Under **Custom domain**:
   - Confirm `rapidio.co.uk` is entered (automatically read from the `CNAME` file).
   - Once DNS propagates, check **Enforce HTTPS**.

### 2. DNS Settings at your Domain Registrar (for `rapidio.co.uk`)

Configure the following records in your DNS provider (e.g., Cloudflare, Namecheap, Google Domains, Route 53):

#### A Records (Apex Domain `@` or `rapidio.co.uk`)
Point to GitHub Pages IP addresses:
- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

#### CNAME Record (Subdomain `www`)
- Host: `www`
- Value: `<your-github-username>.github.io`

---

## Institutional Brand Identity

- **Company**: Rapid IO LTD
- **Jurisdiction**: Registered in England & Wales
- **Official Contact**: `admin@rapidio.co.uk`
- **Design System**: Obsidian Dark Slate (`#06090F`), Electric Cyan (`#00F2FE` / `#06B6D4`), and Monospace System Telemetry (`JetBrains Mono`).
- **Core Pillars**:
  1. Quantitative Simulation & Multi-TB Backtesting Grids
  2. Distributed Actor Systems (Microsoft Orleans & High-Performance .NET)
  3. Electronic Trading Gateways & Real-Time Pricers
  4. Autonomous Agentic Systems (Anthropic Claude 3.5 Sonnet / Opus)
  5. Deterministic Enterprise RAG & Sovereign Air-Gapped Deployments
