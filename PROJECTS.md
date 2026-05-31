# Projects by Hasan Rizvee

A structured map of my public and business-facing work across AI developer workflows, SEO systems, WordPress/WooCommerce products, creative browser tools, e-commerce infrastructure, and institutional digital systems.

---

## Project Categories

| Category | Focus |
|---|---|
| AI Dev Workflow | Agentic development systems, multimodel coding workflows, local-first automation |
| SEO & Growth | Local SEO tools, technical SEO systems, content operations, AEO workflows |
| WordPress/WooCommerce | Plugins, e-commerce tools, payment logic, verification systems |
| Creative Tools | Browser-based design, image, prompt, and utility tools |
| Business Systems | Booking, stock, institutional, and operational platforms |
| Fashion-Commerce | Apparel, e-commerce, product content, conversion infrastructure |

---

## Featured Projects

---

## 1. MultiModel Dev OS

**Repository:** [rizvee/multimodel-dev-os](https://github.com/rizvee/multimodel-dev-os)

**Type:** AI developer workflow system  
**Status:** Public  
**Focus:** Codex, Antigravity, Cursor, Claude, Gemini, VS Code, multimodel coding agents

### What it does

MultiModel Dev OS creates a portable AI development workspace that gives different AI coding tools the same project brain.

It uses root-level project contracts and a structured `.ai/` layer to reduce context fragmentation across coding agents.

### Core files

```txt
AGENTS.md
MEMORY.md
TASKS.md
RUNBOOK.md
.ai/
```

### Key use cases

* Initialize AI-ready project structures
* Standardize instructions across coding agents
* Reduce context loss between tools
* Maintain portable project memory
* Support token-efficient development workflows
* Add tool-specific adapters without making any one tool the source of truth

### Command

```bash
npx multimodel-dev-os@latest init
```

### Why it matters

Modern AI development is no longer single-tool. Developers switch between Codex, Cursor, Claude Code, Gemini, Antigravity, VS Code, and other assistants. This project solves the context-fragmentation problem by creating a portable source of truth inside the repository.

---

## 2. LocalRank OS

**Repository:** [rizvee/LocalRank-OS](https://github.com/rizvee/LocalRank-OS)

**Type:** Local-first SEO operating system
**Status:** Public
**Focus:** Local SEO, agency workflows, audits, reporting, rank tracking

### What it does

LocalRank OS is a deterministic SEO operating system designed for agencies and operators. It manages clients, audits websites, tracks keywords, monitors algorithm impact, runs competitor gap analysis, and supports local-first SEO operations.

### Core modules

* Client Command Center
* Website crawler and audit engine
* PDF reporting
* Google Business Profile workflows
* Keyword rank tracker
* Competitor gap intelligence
* Algorithm monitoring
* AI Copilot context layer
* Content operations and approvals
* Universal search
* Backup and export workflows

### Stack

```txt
Next.js
TypeScript
SQLite
Drizzle ORM
Tailwind CSS
Vitest
Lucide React
```

### Why it matters

Most SEO tools are cloud-heavy, subscription-heavy, and scattered. LocalRank OS explores a local-first model where agencies can manage structured SEO operations with deterministic rules, offline-friendly data, and operator-controlled workflows.

---

## 3. Code-Steward

**Repository:** [rizvee/Code-Steward](https://github.com/rizvee/Code-Steward)

**Type:** AI-native technical debt remediation tool
**Status:** Public
**Focus:** AI-generated code cleanup, local-first analysis, PR-safe remediation

### What it does

Code-Steward is a local-first concept for detecting, explaining, and fixing AI-generated code rot.

### Core ideas

* Technical Debt Ratio
* AI-smell detection
* Shadow workspace remediation
* Local-first analysis
* Pull request generation
* Verification metadata
* MCP tool bridge
* Repeatable audit → plan → execute → verify workflow

### Why it matters

AI-generated code can move fast but also create hidden maintenance risk. Code-Steward focuses on identifying that risk, making it explainable, and turning cleanup into a reviewable workflow.

---

## 4. WooAdvancePay

**Repository:** [rizvee/WooAdvancePay](https://github.com/rizvee/WooAdvancePay)

**Type:** WooCommerce plugin
**Status:** Public
**Focus:** Partial payment, advance payment, COD control, locality-based payment logic

### What it does

WooAdvancePay extends WooCommerce by allowing store owners to collect advance or partial payments for cash-on-delivery orders based on specific locality rules.

### Key features

* Percentage-based advance payment
* Fixed-amount advance payment
* Locality-based rules
* WooCommerce checkout integration
* COD-focused cash-flow control
* Useful for Bangladesh-style e-commerce delivery operations

### Why it matters

Cash-on-delivery can create cancellation risk and cash-flow problems. This plugin solves a real operational friction point for e-commerce businesses.

---

## 5. Certificate Verification for WP

**Repository:** [rizvee/Certificate-Verification-for-WP](https://github.com/rizvee/Certificate-Verification-for-WP)

**Type:** WordPress plugin
**Status:** Public
**Focus:** Certificate verification, educational institutions, admin records, AJAX verification

### What it does

Certificate Verification for WP lets educational institutions manage student certificate records and publish a frontend verification form where users can verify certificate authenticity using Roll/ID.

### Key features

* Custom database table
* Admin certificate management
* Add, edit, delete certificate records
* Bulk CSV import
* Shortcode-based frontend verification
* AJAX-powered search
* Roll/ID-based lookup
* Nonce protection
* Sanitization and escaping
* Prepared SQL queries

### Why it matters

Educational institutions need simple, trustworthy certificate verification systems. This plugin gives them a lightweight WordPress-native option.

---

## 6. PixWeave

**Repository:** [rizvee/PIXWEAVE](https://github.com/rizvee/PIXWEAVE)
**Live:** [rizvee.github.io/PIXWEAVE](https://rizvee.github.io/PIXWEAVE/)

**Type:** Static browser tool
**Status:** Public
**Focus:** Privacy-first collage maker, local-only image processing

### What it does

PixWeave is a browser-based photo collage maker that runs locally. User photos never leave the device.

### Key features

* 38 collage layouts
* 20 frame styles
* 11 filters
* 12 aspect ratios
* High-resolution export
* PWA support
* Offline-capable architecture
* Static hosting friendly
* Local image rendering

### Stack

```txt
HTML
CSS
JavaScript
html2canvas
PWA
JSON-LD
Open Graph
```

### Why it matters

It is a practical example of a privacy-first, static, SEO-ready creative tool that can run without a backend.

---

## 7. PromptForge

**Repository:** [rizvee/PromptForge](https://github.com/rizvee/PromptForge)

**Type:** AI prompt library and optimizer
**Status:** Public
**Focus:** Claude, ChatGPT, Gemini, prompt templates, local prompt workflows

### What it does

PromptForge is a browser-based AI prompt library and optimizer for LLM workflows.

### Key features

* 100+ prompt templates
* Prompt search
* Copy to clipboard
* Save favorites locally
* Share via URL
* Bring-your-own-key optimization model

### Why it matters

Prompt quality directly affects output quality. PromptForge turns reusable prompt systems into an accessible browser-based library.

---

## 8. LinkWiz-SaaS

**Repository:** [rizvee/LinkWiz-SaaS](https://github.com/rizvee/LinkWiz-SaaS)

**Type:** WordPress plugin concept
**Status:** Public
**Focus:** Link management, QR codes, URL shortening, bio-links

### What it does

LinkWiz-SaaS is a WordPress-based link management system concept for marketers, influencers, and businesses.

### Key features

* QR code generation
* URL shortening
* Bio-links
* White-label branding
* Monetization-ready plugin architecture

---

## 9. AppointEase

**Repository:** [rizvee/AppointEase](https://github.com/rizvee/AppointEase)

**Type:** PHP appointment booking system
**Status:** Public
**Focus:** Booking, scheduling, AJAX, SMTP, Google Spreadsheet integration

### What it does

AppointEase is a PHP-based appointment booking and scheduling system for businesses and service providers.

### Key features

* Appointment booking flow
* Responsive layout
* AJAX interactions
* Bootstrap 4
* SMTP support
* Google Spreadsheet integration
* Auto-responder email
* Service categorization
* Office-hour restrictions
* Payment integration support

---

## Additional Public Repositories

| Repository                                                                                                               | Area                         |
| ------------------------------------------------------------------------------------------------------------------------ | ---------------------------- |
| [PIXELRIFT](https://github.com/rizvee/PIXELRIFT)                                                                         | Creative/browser tool        |
| [StyleSphere](https://github.com/rizvee/StyleSphere)                                                                     | Fashion/product experience   |
| [stratos](https://github.com/rizvee/stratos)                                                                             | Web/tool experiment          |
| [Cartographia-The-Alchemist-s-Atlas](https://github.com/rizvee/Cartographia-The-Alchemist-s-Atlas)                       | Creative/interactive project |
| [MuseKit](https://github.com/rizvee/MuseKit)                                                                             | Creator toolkit              |
| [SwiftQR](https://github.com/rizvee/SwiftQR)                                                                             | QR utility                   |
| [WordWarp](https://github.com/rizvee/WordWarp)                                                                           | Word/puzzle tool             |
| [The-Color-Thief](https://github.com/rizvee/The-Color-Thief)                                                             | Color utility                |
| [WooAdvancePay-Partial-Payment-for-Woocommerce](https://github.com/rizvee/WooAdvancePay-Partial-Payment-for-Woocommerce) | WooCommerce partial payment  |
| [rizvee.github.io](https://github.com/rizvee/rizvee.github.io)                                                           | GitHub Pages portfolio       |
| [climacast](https://github.com/rizvee/climacast)                                                                         | Weather app                  |
| [VocalAI-Desi](https://github.com/rizvee/VocalAI-Desi)                                                                   | AI/audio concept             |
| [CloudNine](https://github.com/rizvee/CloudNine)                                                                         | Web/app experiment           |
| [Utilvault](https://github.com/rizvee/Utilvault)                                                                         | Developer utilities          |
| [css-art-generator](https://github.com/rizvee/css-art-generator)                                                         | CSS visual tool              |
| [PaletteForge](https://github.com/rizvee/PaletteForge)                                                                   | Color palette tool           |
| [dep-reaper](https://github.com/rizvee/dep-reaper)                                                                       | Dependency/tooling concept   |
| [tracksmith-pro](https://github.com/rizvee/tracksmith-pro)                                                               | Tracking/ops tool            |
| [portfolio-v2](https://github.com/rizvee/portfolio-v2)                                                                   | Portfolio rebuild            |
| [Color-Bloom](https://github.com/rizvee/Color-Bloom)                                                                     | Color/creative project       |
| [StockSync-All-in-one-simple-Stock-Management](https://github.com/rizvee/StockSync-All-in-one-simple-Stock-Management)   | Stock management             |
| [PantryPal](https://github.com/rizvee/PantryPal)                                                                         | Utility/app project          |
| [PixelForge](https://github.com/rizvee/PixelForge)                                                                       | Image processing tool        |

---

## Business-Facing Work

### Savior Lifestyle

**Website:** [saviorlifestyle.com](https://saviorlifestyle.com)

Role: Co-founder and Digital Architect

Focus areas:

* E-commerce operations
* WooCommerce infrastructure
* Product content
* Product page optimization
* SEO
* Analytics
* Meta ads and tracking
* Customer journey optimization
* Apparel brand growth

---

### Culinary Institute of Bangladesh

**Website:** [cibdhk.com](https://cibdhk.com)

Role: Digital systems, SEO, web infrastructure, growth strategy

Focus areas:

* Website architecture
* Landing pages
* SEO/AEO systems
* Course funnel strategy
* Student-facing systems
* Certificate verification
* Knowledge base architecture
* Analytics and tracking

---

## Project Philosophy

Every project should answer at least one of these questions:

1. Does it solve a real operational problem?
2. Does it reduce repeated manual work?
3. Does it improve search visibility or conversion?
4. Does it create a reusable workflow?
5. Does it make a business move faster?
6. Does it make AI-assisted development more reliable?

If not, it is probably not worth building.

---

## Connect

* Portfolio: [hasanrizvee.info](https://hasanrizvee.info)
* GitHub: [github.com/rizvee](https://github.com/rizvee)
* GitHub Pages: [rizvee.github.io](https://rizvee.github.io)
* LinkedIn: [linkedin.com/in/hasanrizvee](https://www.linkedin.com/in/hasanrizvee)
* Savior Lifestyle: [saviorlifestyle.com](https://saviorlifestyle.com)
* CIB: [cibdhk.com](https://cibdhk.com)
