# Awesome-Corporate-WIKI-Internal-Knowledge-Base

## Top Corporate Wiki & Internal Knowledge Base Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Team Documentation, Knowledge Sharing & AI-Assisted Search*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Corporate Wiki & Internal Knowledge Base**. These tools help teams capture, organize, and retrieve institutional knowledge—covering everything from simple documentation wikis to AI-powered knowledge platforms with semantic search and automated content generation.

**Examples** include Notion, Confluence, Slite, GitBook, Slab, Nuclino, Document360, Bloomfire, Guru, and Zoho Wiki (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted wikis, open-source knowledge bases, and community-driven documentation platforms—ideal for organizations seeking data sovereignty and predictable costs over per-user SaaS subscriptions.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Notion](https://www.notion.so/)** | All-in-one workspace combining docs, wikis, and databases. Free for individuals with unlimited pages; team plans add collaboration and admin features. Notion AI available as add-on . | Plus: $10/user/month; Business: $15/user/month; Enterprise: quote-only . | **Free**: unlimited pages for individuals; team workspaces have **limited blocks** for 2+ members; file uploads max **5 MB**; **7-day** page history . |
| **[Confluence](https://www.atlassian.com/software/confluence)** | Atlassian's enterprise wiki and documentation platform. Deep integration with Jira and the Atlassian ecosystem. Rovo AI credits included on paid plans . | Standard: $5.78/user/month; Premium/Enterprise: quote-only . | **Free forever**: up to **10 users**, **2 GB** file storage, community support. Paid trial: **7 days** . |
| **[Slite](https://slite.com/)** | Knowledge base with AI-powered search and verification. Positioned for async teams needing structured documentation. 14-day free trial on all plans . | Standard: $8/user/month (annual); Knowledge Suite: $20/user/month; Enterprise: quote-only . | **No free tier**. **14-day free trial** with Standard plan features. Read-only users and audit logs only on Enterprise . |
| **[GitBook](https://www.gitbook.com/)** | Documentation platform with Git sync, API playground, and AI assistant. Popular for public-facing docs and developer documentation . | Essential: $65/site/month + $12/user/month; Ultimate: $249/site/month + $12/user/month . | **Free**: single user, Git sync, interactive API playground, LLM optimization. **Community plan** free for qualifying non-profits/open-source (excludes SAML SSO) . |
| **[Nuclino](https://www.nuclino.com/)** | Lightweight team wiki with visual workspace. Simple, transparent pricing. No credit card required for trial . | Starter: $6/user/month; Business: $10/user/month (adds SAML SSO) . | **Free**: up to **50 items** (documents), **3 canvases**, **2 GB** total storage. **No credit card** for trial . |
| **[Document360](https://document360.com/)** | Knowledge base software for SaaS products and internal teams. Positioned for customer support and internal documentation . | Starts at **$149/project/month**; enterprise tiers available . | **No free plan**. Free trial available . |
| **[Bloomfire](https://www.bloomfire.com/)** | Enterprise knowledge platform with AI search. Quote-only pricing on multi-year contracts. No public price list . | Quote-only (Team, Department, Enterprise tiers) . | **No free plan**. Guided "Test Drive" demo only; no self-serve signup . |
| **[Zoho Wiki](https://www.zoho.com/wiki/)** | Wiki within the Zoho ecosystem. Simple, affordable documentation tool with basic access controls . | Paid plans available (monthly/annual) . | **Free**: **3 users**, **50 MB** storage, unlimited pages/revisions, SSL, ZIP backup, RSS/Atom, access controls, custom CSS . |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Kherad](https://github.com/mohammadmaso/kherad)** | [![Stars](https://img.shields.io/github/stars/mohammadmaso/kherad?style=social&color=white)](https://github.com/mohammadmaso/kherad/stargazers) | **The most complete open-source Notion-style wiki with real Git underneath.** Self-hosted, block editor for non-technical authors; every save is a real commit, every publish goes through merge-request review. Includes **"Ask the knowledge base"** RAG chat with cited sources, **AI specialist agents** that draft pages, document/voice ingest (PDF/Office/OCR/voice → markdown), link graph, per-bundle permissions, and Postgres full-text search. Docker Compose deployment. Built for single-organization internal docs, not multi-tenant SaaS . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Wiki.js](https://github.com/requarks/wiki)** | [![Stars](https://img.shields.io/github/stars/requarks/wiki?style=social&color=white)](https://github.com/requarks/wiki/stargazers) | Modern, lightweight wiki engine (Node.js). Markdown editing, full-text search, granular permissions, and authentication integrations (LDAP, SAML, OAuth2). Self-hosted with Docker. |
| **[Outline](https://github.com/outline/outline)** | [![Stars](https://img.shields.io/github/stars/outline/outline?style=social&color=white)](https://github.com/outline/outline/stargazers) | Team knowledge base and wiki (Node.js/React). Real-time collaborative editing, Slack integration, and public sharing. Self-hosted or cloud. |
| **[BookStack](https://github.com/BookStackApp/BookStack)** | [![Stars](https://img.shields.io/github/stars/BookStackApp/BookStack?style=social&color=white)](https://github.com/BookStackApp/BookStack/stargazers) | Simple, self-hosted wiki with a book/chapter/page hierarchy. WYSIWYG editor, full-text search, and role-based permissions. PHP/Laravel stack. |

**Frameworks for building custom systems**: Combine **Wiki.js** or **BookStack** for traditional hierarchical documentation, **Outline** for real-time collaborative editing, and **Kherad** for AI-assisted knowledge capture with Git-backed review workflows—all deployable via Docker without per-user SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Internal knowledge bases often contain sensitive operational and strategic information; enforce role-based access, audit logging, and data retention policies.
- **Free tier limits vary significantly and change frequently.** Confluence offers a genuine free tier for 10 users with 2 GB storage , Zoho Wiki caps at 3 users and 50 MB , and Nuclino limits to 50 items and 2 GB . Notion's free tier restricts team workspaces to a limited block count . Bloomfire has **no free plan** and quote-only enterprise pricing . Always verify current limits against vendor pages before committing.

---

**Made for documentation teams, engineering managers, operations leads, and developers building knowledge infrastructure.**  
Let's make corporate knowledge sharing more open, searchable, and AI-assisted.
