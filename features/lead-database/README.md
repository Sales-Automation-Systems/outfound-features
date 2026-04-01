# Lead Database

### Your Data. Your Prospects. Fully Owned.

Outfound's lead database is fundamentally different from every other prospecting tool. Instead of buying access to a third-party database you can't control, Outfound builds *your own* lead database automatically from your campaign activity -- and gives you full ownership, full API access, and full export capability.

Every prospect you've ever contacted, enriched with company data, searchable, filterable, and accessible through your own API. This is your outbound intelligence asset, and it grows every time you send an email.

---

## How It Gets Populated

### Automatic Population from Campaigns
Every time a campaign sends an email, the prospect data flows into your lead database automatically. This includes:

- **Person data** -- Name, email, title, seniority, department, LinkedIn profile, email service provider
- **Company data** -- Company name, domain, industry, headcount range, LinkedIn profile, revenue range
- **Keywords** -- Technology tags, industry terms, and custom attributes associated with the company

This happens silently in the background. You don't configure it, you don't trigger it -- your lead database grows as your outbound operation runs.

**Why it's a game-changer:** With other tools, your prospect data lives inside the sending platform. If you switch platforms, you lose it. If the platform shuts down, it's gone. With Outfound, your prospect data lives in *your* database, automatically enriched from every platform you use (Instantly, Smartlead, EmailBison).

### API Push
You can also push leads directly into your database via API:

- **Webhook endpoint** for real-time ingestion
- **Combined person + company payloads** ensuring data integrity
- **Idempotent upserts** -- pushing the same lead twice updates it, doesn't duplicate it
- **Async processing** -- the API accepts data immediately and processes it in the background for high throughput

This means you can feed leads from any source: CRM exports, list purchases, enrichment tools, internal databases, or custom scrapers. Everything ends up in one unified database.

---

## Search & Filtering

### People Search
Find any prospect in your database with filters on:
- Name (first, last)
- Email
- Job title
- Seniority level
- Department
- Email service provider
- LinkedIn profile
- Company domain

### Company Search
Find any company with filters on:
- Company name
- Domain
- Industry
- Headcount range
- LinkedIn profile
- Keywords / technology tags
- Revenue range

### Dynamic Catalog
As data flows into your database, Outfound automatically builds filter catalogs -- dropdown menus populated with the actual values in your data. No hardcoded industry lists. If your prospects work in "Developer Tools" and "Climate Tech," those values appear automatically in your filters.

**Why it matters:** Third-party databases force you into their taxonomy. Outfound's catalogs reflect *your* data, which means filters always match the actual prospect population you've built.

---

## Person Enrichment

Given a list of email addresses, Outfound returns everything it knows about those people:

- Full person profile (name, title, seniority, department, etc.)
- Full company profile (name, domain, industry, headcount, revenue, etc.)
- Associated keywords and technology tags

Batch enrichment supports up to 100 emails per request, making it efficient for CRM sync, list validation, or pipeline enrichment workflows.

**Why it matters:** Your lead database isn't just a list -- it's an enrichment source. Any tool in your stack can query Outfound to enrich contact data with the intelligence you've built over months of outbound activity.

---

## Data Ownership

This is the philosophical core of the lead database:

**You own the data.** Not Outfound. Not your sending platform. You.

- **Full export** -- Download your entire database as CSV at any time
- **API access** -- Query your data programmatically with your own API keys
- **No lock-in** -- Your data is yours whether you use Outfound for 1 month or 10 years
- **Multi-platform aggregation** -- Data from Instantly, Smartlead, and EmailBison all flows into the same database

**Why it's a game-changer:** In the current outbound ecosystem, your sending platform holds your data hostage. You've spent months building a prospect list, enriching it, and refining it -- and it lives on someone else's server behind their API limits. Outfound flips this. Your outbound operation generates data, and that data belongs to you.

---

## Export System

Outfound's export system is built for scale:

- **Background processing** -- Exports run asynchronously, so you don't wait around
- **Progress tracking** -- See how many rows have been processed
- **Memory-efficient streaming** -- Even million-row exports won't crash the system
- **Secure download links** -- Time-limited URLs for downloading exports
- **Automatic cleanup** -- Old exports are cleaned up after 3 months

---

## API Access

The lead database has its own dedicated API with:

### Rate Limiting Tiers

| Tier | Requests/Hour |
|---|---|
| Basic | 100 |
| Standard | 1,000 |
| Premium | 10,000 |
| Enterprise | 100,000 |

### Multiple API Keys
Create multiple API keys per organization. Give different keys to different systems or team members. Regenerate or revoke keys without affecting others.

### Scoped Access
API keys are scoped to your organization. Every query is automatically filtered to only return your data. There's no way to accidentally (or intentionally) access another organization's prospects.

---

## Keyword Intelligence

Companies in your database are tagged with normalized keywords:

- Technology stack tags
- Industry vertical identifiers
- Custom attributes from campaign enrichment data

Keywords are deduplicated and normalized across your entire database, so "Machine Learning" and "machine learning" and "ML" can be mapped to a single canonical keyword. This enables structured filtering that actually works across messy real-world data.

---

## Reusability

The lead database isn't a static archive -- it's a living asset you can reuse:

- **Re-target** -- Find prospects from old campaigns who were "neutral" and run new campaigns targeting them
- **Enrich CRM** -- Push enrichment data from your lead database into your CRM
- **Build lists** -- Search and filter to build new campaign lists from your existing data
- **Analyze patterns** -- Use the AI Data Agent to query your lead database for insights
- **Feed other tools** -- API access means any tool in your stack can query your prospects

---

## What This Means For Your Team

- **Ops teams** build a growing, reusable asset instead of disposable campaign lists
- **Sales teams** can look up any prospect they've ever contacted with full context
- **Data teams** get API access to build custom enrichment and analysis workflows
- **Leadership** sees outbound as an investment that compounds -- every campaign makes the database more valuable
- **Finance teams** can quantify the data asset built by the outbound operation
