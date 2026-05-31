# 📂 Public & Business-Facing Work by Hasan Rizvee

A comprehensive, production-grade showcase of my software engineering, automated systems, custom WordPress plugins, Technical SEO setups, and 3D fashion-commerce work.

---

## 🧭 Directory of Project Categories

Use the links below to jump directly to specific areas of work:

| Category | Focus | Core Tools & Technologies |
|---|---|---|
| [🤖 AI Dev Workflows](#1-multimodel-dev-os) | Agentic development systems, portable context layers, and AI debt janitors | Codex, Antigravity, Cursor, Claude Code, NPX, MCP |
| [📍 Technical & Local SEO](#2-localrank-os) | Local rank trackers, website auditing crawlers, algorithm alerts | Next.js, TypeScript, SQLite, Drizzle, GSC API |
| [💳 E-Commerce & WordPress Products](#4-wooadvancepay) | Custom partial checkout logic, database verification engines, link managers | PHP, WordPress DB Layer, WooCommerce API, AJAX, CSV |
| [🎨 Creative Browser Tools](#6-pixweave) | Privacy-first canvas builders, PWA image filters, prompt optimizers | HTML5 Canvas, JS, PWA, Local-first image ETL |
| [🐍 Python & AI Automation Lab](#-python--ai-automation-lab) | Headless web spiders, background syncs, Telegram loggers, custom agent scripts | Playwright, Pandas, OpenAI/Claude API, Telegram bots |
| [👔 Fashion & Business Operations](#-fashion--business-operations) | Custom e-commerce platforms and training institute digital systems | WooCommerce, Google Classroom API, CLO3D, Cinema 4D |

---

## 🚀 Featured Production Builds

---

## 1. MultiModel Dev OS
> **Repository:** [rizvee/multimodel-dev-os](https://github.com/rizvee/multimodel-dev-os)  
> **Status:** Public Production Concept  
> **Stack:** Node.js · NPX Command Runner · Markdown Engine · Context Engineering

```
  ┌────────────────────────────────────────────────────────┐
  │                 MULTIMODEL DEV OS LAYERS               │
  ├────────────────────────────────────────────────────────┤
  │ [Cursor / Codex]  ◄───┐                                │
  │ [Claude Code]     ◄───┼───► [Shared Memory Layer]     │
  │ [Gemini Agent]    ◄───┘     (.ai/, MEMORY.md, TASKS.md)│
  └────────────────────────────────────────────────────────┘
```

### 👤 Target User
AI-assisted software developers, teams working with mixed AI editors (e.g. Cursor + Claude Code + Gemini), and engineering managers who want to standardize codebase guidelines across various machine learning models.

### 💡 Core Operational Problem Solved
Modern AI coding tools are extremely powerful, but they write code in isolation. When you switch from Cursor to Gemini or a Claude terminal, the new AI doesn't know what you just did. It wastes tokens re-analyzing files, forgets architectural rules, and introduces conflicting code patterns. **MultiModel Dev OS** creates a portable, tool-agnostic "Shared Memory Layer" directly in the git repository to keep all models perfectly synchronized.

### 🌟 Key Features
* **Zero-Dependency Initialization:** Runs instantly using simple NPX scripts to establish standard repository guidelines.
* **Structured System Files:** Auto-generates standard agent instruction layers:
  * `AGENTS.md` - Explicit behavioral guidelines and model strengths.
  * `MEMORY.md` - Key project boundaries, decisions, and system history.
  * `TASKS.md` - Granular checklist to prevent duplicate efforts.
  * `RUNBOOK.md` - Core commands, deployment paths, and build scripts.
* **Automated `.ai/` context folder:** Scaffolds configuration details for custom developer pipelines.

### 💻 Command
```bash
npx multimodel-dev-os@latest init
```

### 📈 Business & Team Outcome
Eliminates context-loss overhead, reduces duplicate debugging sessions, and cuts API token spending by up to 40% by maintaining absolute clarity of current project states.

---

## 2. LocalRank OS
> **Repository:** [rizvee/LocalRank-OS](https://github.com/rizvee/LocalRank-OS)  
> **Status:** Public Pre-release  
> **Stack:** Next.js 14 · TypeScript · SQLite · Drizzle ORM · Tailwind CSS · Vitest

### 👤 Target User
B2B SEO agencies, local consultants, and marketing operators managing multiple brick-and-mortar clients.

### 💡 Core Operational Problem Solved
Traditional local rank trackers are highly expensive, charge hefty monthly subscriptions, and hold customer data hostage in proprietary cloud environments. **LocalRank OS** is a fast, local-first operating system that gives agencies 100% ownership of their SEO audit, keyword rank tracking, and customer PDF reporting workflows.

### 🌟 Key Features
* **Client Command Center:** Single unified dashboard to manage multiple clients, web domains, and local business profiles.
* **Deterministic Keyword Rank Tracker:** Queries organic search results directly through configurable scraping intervals.
* **SEO Site Audit Crawler:** On-page crawler that audits title tags, H1-H6 structures, image alt attributes, response codes, and schema completeness.
* **Local Business Workflows:** Checklists and update pipelines for Google Business Profile optimization.
* **Automated PDF Executive Reporting:** Generates high-quality, white-labeled progress PDFs at the click of a button.
* **Local-First Architecture:** SQLite storage ensures instantaneous loading speeds and zero recurring database server charges.

### 📈 Business & Team Outcome
Enables smaller digital agencies to scale to dozens of local clients without incurring hundreds of dollars in monthly SEO SaaS fees, while keeping client marketing data entirely confidential.

---

## 3. Code-Steward
> **Repository:** [rizvee/Code-Steward](https://github.com/rizvee/Code-Steward)  
> **Status:** Architecture Proposal & Prototyping  
> **Stack:** Python · MCP (Model Context Protocol) Bridge · Custom AST Parsers

### 👤 Target User
Engineering leads and principal developers managing codebases that receive heavy contributions from AI developers.

### 💡 Core Operational Problem Solved
AI coding tools generate code at an unprecedented rate, but they frequently introduce "AI Smell"—unnecessary helper libraries, duplicate functions, dead imports, missing docstrings, and architectural bloat. **Code-Steward** acts as an automated, AI-native janitor that runs continuously to clean up code, evaluate debt, and submit clean refactoring PRs.

### 🌟 Key Features
* **Technical Debt Ratio (TDR) Calculator:** Automatically scans new files and assigns a numerical debt score based on readability, duplicate functions, and typical AI output patterns.
* **Anomalous "AI-Smell" Detector:** Flag typical LLM habits (such as overly verbose comments, repetitive try-catch blocks, and missing type definitions).
* **Shadow Workspace Remediation:** Spawns an isolated background environment to test fixes without interrupting active developer branch code.
* **Automated Verified PR Builder:** Generates highly structured, ready-to-merge Pull Requests containing precise diffs, lint checks, and explanation notes.
* **MCP Integration:** Allows AI IDEs to query Code-Steward tools directly during normal development.

---

## 4. WooAdvancePay
> **Repository:** [rizvee/WooAdvancePay](https://github.com/rizvee/WooAdvancePay)  
> **Status:** Production Ready (Open Source)  
> **Stack:** PHP · WordPress Plugin Core · WooCommerce API · WordPress database layer

### 👤 Target User
E-Commerce business owners operating in South Asian and emerging markets (like Bangladesh) where Cash-On-Delivery (COD) is the dominant payment method.

### 💡 Core Operational Problem Solved
Cash-On-Delivery is convenient for buyers but dangerous for merchants. Fake orders, customer unavailability, or impulsive change of mind result in high Return-to-Origin (RTO) rates. The retailer loses shipping fees twice (delivery and return) and has their inventory tied up for days. **WooAdvancePay** solves this by forcing a customizable partial payment (like a delivery security deposit) during checkout, validating the customer's intent before dispatch.

### 🌟 Key Features
* **Dynamic Partial Pricing:** Apply advance payment requests either as a flat amount (e.g. 100 BDT shipping fee) or a percentage of the total order value.
* **Locality-Based Payment Logic:** Dynamically triggers advance payment rules based on the customer's city or shipping zone (e.g. free COD inside the city, required advance outside).
* **Seamless Checkout Integration:** Integrates into native WooCommerce gateways without breaking custom mobile checkouts or multi-step forms.
* **Order Status Automation:** Moves unpaid advance orders into a "Pending Verification" state automatically, keeping the order flow organized.

### 📈 Business & Team Outcome
Directly reduced e-commerce customer return rates (RTO) by up to 60%, drastically cutting down logistics costs and keeping high-demand apparel inventory available on the store shelf.

---

## 5. Certificate Verification for WP
> **Repository:** [rizvee/Certificate-Verification-for-WP](https://github.com/rizvee/Certificate-Verification-for-WP)  
> **Status:** Public Production-Grade  
> **Stack:** PHP · WordPress DB Manager · AJAX Interface · SQL Prepared Statements

### 👤 Target User
Training academies, professional institutes, universities, and educational platforms using WordPress.

### 💡 Core Operational Problem Solved
Academic forgery is a growing problem. Employers constantly call training institutes manually to verify if a graduate’s certificate is real. This wastes administrative hours and delays hiring. **Certificate Verification for WP** establishes a bulletproof, frontend-searchable certificate registry on WordPress where employers can verify credentials instantly.

### 🌟 Key Features
* **Custom Optimized DB Schema:** Registers a lightweight, high-performance database table for certificate records, separate from standard WordPress post meta.
* **Secure Roll/ID Lookup Engine:** Prevents enumeration attacks by validating query requests using strict sanitization, type casting, and nonce verification.
* **Instant AJAX Search:** Dynamic frontend loading system allows search queries to return results instantly without reloading the parent webpage.
* **Bulk CSV Import Manager:** Lets administrators upload thousands of student certificate records (student name, roll, grade, issue date) within seconds.

### 📈 Business & Team Outcome
Eliminates 100% of manual email and phone verification requests, while offering graduates and corporate employers a professional, high-speed verification channel.

---

## 6. PixWeave
> **Repository:** [rizvee/PIXWEAVE](https://github.com/rizvee/PIXWEAVE)  
> **Live Site:** [rizvee.github.io/PIXWEAVE](https://rizvee.github.io/PIXWEAVE/)  
> **Status:** Live Public PWA  
> **Stack:** Vanilla HTML5 · CSS Grid & Flexbox · JavaScript Canvas API · html2canvas · JSON-LD Schema

### 👤 Target User
Content creators, fashion operators, social media managers, and privacy-conscious mobile users.

### 💡 Core Operational Problem Solved
Most online photo collage and grid makers require uploading images to third-party cloud servers, leading to slow processing times, watermarked exports, premium paywalls, and privacy risks. **PixWeave** processes images completely in the browser sandbox. User data never touches a server.

### 🌟 Key Features
* **38 Modular Layouts & Grid Engines:** Supports responsive photo arrangement across dynamic grids, panels, and frames.
* **Local Image Pipeline:** Employs advanced canvas scaling to merge photos without degrading image resolution.
* **High-Resolution Export:** Renders and downloads high-quality JPG/PNG collages ready for web or print.
* **Progressive Web App (PWA):** Installs natively on mobile and desktop devices and remains 100% operational offline.
* **Semantic SEO Architecture:** Formatted with rich JSON-LD data schema to rank organically in search engines as a utility app.

---

## 7. PromptForge
> **Repository:** [rizvee/PromptForge](https://github.com/rizvee/PromptForge)  
> **Status:** Live Utility App  
> **Stack:** HTML5 · CSS3 · Pure ES6 JavaScript · LocalStorage ETL

### 👤 Target User
AI operators, prompt engineers, copywriters, and developers using Anthropic, OpenAI, or Gemini.

### 💡 Core Operational Problem Solved
Copying and pasting common AI system instructions, prompts, and variable templates is highly repetitive and leads to lost formatting and inconsistent responses. **PromptForge** is a fast, local-first prompt library organizer that allows users to manage and optimize system templates.

### 🌟 Key Features
* **100+ Production-Ready Templates:** Preloaded with proven prompts for development, SEO copywriting, and code reviews.
* **Dynamic Variable Placeholders:** Parses prompts to identify input fields, allowing users to populate inputs on-the-fly.
* **Offline-First Storage:** Automatically saves favorites and custom prompt categories using secure browser LocalStorage.
* **Bring-Your-Own-Key Framework:** Integrates directly with LLM API endpoints for localized prompt optimization scripts.

---

## 🐍 Python & AI Automation Lab

I use Python as the ultimate operational utility belt to build web scrapers, data parsers, and e-commerce synchronization engines that run quietly in the background.

```
  ┌────────────────────────────────────────────────────────┐
  │                   PYTHON UTILITIES MAP                 │
  ├────────────────────────────────────────────────────────┤
  │ [WooCommerce REST] ──► [Spreadsheet Logs] ──► [Telegram]│
  │ [SerpAPI Crawler]  ──► [Rank Tracker]     ──► [PDF Rpt] │
  │ [Playwright/Sel.]  ──► [Competitive Gap]  ──► [JSON]    │
  └────────────────────────────────────────────────────────┘
```

### 1. Multi-Channel E-Commerce Synchronizer
* **The Task:** Manages and syncs stock and logistics spreadsheets automatically when orders occur on WooCommerce.
* **The Script:** A Python runner powered by the `WooCommerce REST API`, `openpyxl`, and `pandas`. It fetches hourly order logs, cross-checks product SKU codes, updates stock counts, compiles raw metrics, and broadcasts shipping details to operational Telegram channels.
* **Impact:** Reduced manual double-entry inventory tracking by 12 hours every single week.

### 2. Technical SEO Competitive Spider
* **The Task:** Audits competitor landing pages and maps content structures automatically.
* **The Script:** A programmatic crawler that takes target domains, parses sitemaps using `BeautifulSoup` and `requests`, maps deep internal links, grabs H1-H3 titles, extracts keyword occurrences, and compiles competitor content gap reports into clean JSON sheets.
* **Impact:** Drastically speeds up keyword research and topical clustering planning.

### 3. Maps Pack Rank & Delta Tracker
* **The Task:** Monitors localized business rankings inside Google Maps Map Pack for target keywords.
* **The Script:** Integrates `SerpAPI` with custom proxy networks and coordinate grids using Python. It loops through specified geo-locations, records the ranking numbers, calculates ranking changes (deltas) over the last week, and formats highlights into agency reporting sheets.
* **Impact:** Replaced manual ranking search queries for dozens of business locations.

### 4. Custom AI Content Pre-Processor
* **The Task:** Generates structured article drafts according to semantic SEO guidelines.
* **The Script:** Connects `Anthropic API` (Claude) or `OpenAI API` using Python script runners. It reads raw topic files, runs automated Google queries to pull top search intent parameters, injects strict JSON-LD templates, and writes drafts structured with clean semantic Markdown headers.

---

## 👔 Business-Facing Operations

I bridge the gap between engineering and real-world operations by designing digital systems for successful organizations.

### Co-Founder & Digital Architect | Savior Lifestyle
* **Website:** [saviorlifestyle.com](https://saviorlifestyle.com)  
* **Operational Focus:** Scalable apparel e-commerce infrastructure.
* **Key Achievements:**
  * Configured reliable server hosting environments to manage seasonal traffic peaks.
  * Designed custom conversion-focused landing pages and interactive checkout workflows.
  * Implemented advanced server-side conversion tracking (Meta Pixel, Google Tag Manager).
  * Reduced delivery cancellation rates through custom software solutions.

### Systems Architect & Search Strategist | Culinary Institute of Bangladesh
* **Website:** [cibdhk.com](https://cibdhk.com)  
* **Operational Focus:** Institutional educational platforms and student workflows.
* **Key Achievements:**
  * Built high-speed training course landing pages with rapid loading scores.
  * Developed secure online student certificate verification networks.
  * Architected local search strategies that established CIB as a dominant training brand online.
  * Implemented student tracking setups and event registrations.

---

## 📂 Additional Public Repositories

An overview of my additional open-source code experiments, creative browser platforms, and operational utilities:

| Repository | Primary Area | Tech Stack | Brief Summary |
|---|---|---|---|
| [StyleSphere](https://github.com/rizvee/StyleSphere) | Fashion / Visual | HTML, CSS, JS | Dynamic web showcase for catalog visual design. |
| [PIXELRIFT](https://github.com/rizvee/PIXELRIFT) | Creative Tool | HTML, CSS Canvas | Browser utility for visual manipulation. |
| [StockSync](https://github.com/rizvee/StockSync-All-in-one-simple-Stock-Management) | Business Sys | PHP, MySQL, CSS | Simplified inventory manager for physical items. |
| [AppointEase](https://github.com/rizvee/AppointEase) | Business Sys | PHP, AJAX, Bootstrap | Office hour booking form with Google sheets logs. |
| [LinkWiz-SaaS](https://github.com/rizvee/LinkWiz-SaaS) | Growth Tool | PHP, WordPress | Marketer link shortener and bio-link creator. |
| [MuseKit](https://github.com/rizvee/MuseKit) | Creative Tool | JS, CSS, PWA | Media tools for background ambient audio/loops. |
| [SwiftQR](https://github.com/rizvee/SwiftQR) | Utility | JS, Canvas API | Quick QR code builder with design customizers. |
| [WordWarp](https://github.com/rizvee/WordWarp) | Puzzle Game | Vanilla JS, CSS | Interactive words puzzle and challenge game. |
| [PaletteForge](https://github.com/rizvee/PaletteForge) | Creative Tool | Vanilla JS, Canvas | Color layout generator for designers. |
| [The-Color-Thief](https://github.com/rizvee/The-Color-Thief) | Utility | HTML5, Canvas | Extract core palette shades from uploaded photos. |
| [css-art-generator](https://github.com/rizvee/css-art-generator) | Visual Tool | CSS, JS Canvas | Pure CSS shape engine and art canvas exporter. |
| [VocalAI-Desi](https://github.com/rizvee/VocalAI-Desi) | AI Concept | Python, API | Audio synthesis and transcription layout wrapper. |
| [climacast](https://github.com/rizvee/climacast) | Weather App | JS, OpenWeather | Clean weather forecast checker with maps. |
| [dep-reaper](https://github.com/rizvee/dep-reaper) | Dev Tool | Node.js, CLI | Scans and lists outdated codebase dependencies. |
| [tracksmith-pro](https://github.com/rizvee/tracksmith-pro) | Ops Tool | JS, DB Layer | Simple delivery tracking and timeline manager. |
| [PantryPal](https://github.com/rizvee/PantryPal) | Utility App | HTML, CSS, JS | Local storage grocery lists and expiring items bot. |
| [PixelForge](https://github.com/rizvee/PixelForge) | Creative Tool | JS Canvas | Simple PWA web photo editing and canvas filter tool. |
| [Color-Bloom](https://github.com/rizvee/Color-Bloom) | Creative Tool | JS Canvas | Interactive mouse particles particle emitter. |
| [CloudNine](https://github.com/rizvee/CloudNine) | Web Concept | HTML, CSS, JS | Concept booking interface with slider transitions. |
| [Utilvault](https://github.com/rizvee/Utilvault) | Dev Tool | JS Core | Shared code utility functions for frontend apps. |
| [stratos](https://github.com/rizvee/stratos) | Web Experiment | CSS, HTML | Layout experiment with futuristic gradients. |
| [portfolio-v2](https://github.com/rizvee/portfolio-v2) | Personal | HTML, Tailwind | Early personal website redesign mockup. |
| [Cartographia](https://github.com/rizvee/Cartographia-The-Alchemist-s-Atlas) | Interactive | Canvas API, JS | Interactive canvas map and discovery interface. |

---

## 🧬 Project Execution Philosophy

1. **Operations determine software design.** You cannot engineer a highly reliable e-commerce flow from an academic tower. You must understand delivery logistics, user payment psychology, and inventory margins.
2. **Every script must solve friction.** If an operator has to click five buttons twice a day, those steps deserve to be grouped into a single automated task.
3. **No black-box AI code.** Using AI tools should lead to pristine systems. Maintain rigid context scaffolding, clean lint requirements, and structured refactoring to ship high-speed code with strict architectural controls.
