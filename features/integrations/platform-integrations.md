# Platform Integrations

### Unified Data Across Every Sending Platform

Outfound isn't locked to one email sending tool. It integrates natively with the most popular outbound sending platforms -- Instantly.ai, Smartlead.ai, and EmailBison -- normalizing data from each into a single, consistent data model. One analytics layer, one attribution system, one lead database -- regardless of which platform sends the email.

---

## Supported Platforms

### Instantly.ai
Full integration with Instantly's campaign ecosystem:

**Campaign events captured:**
- Email sent
- Reply received
- Auto-reply received

**Prospect events captured:**
- Lead interested
- Meeting booked
- Meeting completed
- Deal closed
- Out of office
- Wrong person
- Not interested
- Neutral response

**Bounce tracking:**
- Hard bounces
- Temporary (soft) bounces

**Data enrichment:**
- First/last name, company, job title, website, LinkedIn
- Custom variables from Instantly campaigns
- Workspace identification

### Smartlead.ai
Full integration with Smartlead's sending infrastructure:

**Campaign events captured:**
- Email delivered
- Email replied

**Prospect events captured:**
- Interested
- Meeting booked
- Deal closed

**Bounce tracking:**
- Email bounced

**Data enrichment:**
- Lead data with full enrichment extraction
- Message content from replies and sent emails
- Client/workspace identification

### EmailBison
Full integration with EmailBison's campaign tools:

**Campaign events captured:**
- Email sent
- Lead replied
- Manual email sent (non-sequence emails tracked too)

**Prospect events captured:**
- Lead interested

**Bounce tracking:**
- Email bounced

**Data enrichment:**
- Lead email, sender email
- Reply content (HTML to markdown conversion)
- Custom variables for enrichment
- Workspace identification

---

## How Integration Works

### Unified Data Model
Every platform sends different data in different formats. Outfound normalizes everything into a single data model:

- **Campaign events** → Same format regardless of source
- **Prospect data** → Consistent fields across platforms
- **Email conversations** → Unified inbox entries
- **Bounce data** → Standardized bounce tracking
- **Enrichment data** → Normalized from custom fields/variables

This normalization happens automatically at the data ingestion layer. You don't configure it, map fields, or handle edge cases.

### Platform-Specific Webhook Handlers
Each platform has its own webhook handler that understands the platform's payload format, event types, and data structure. These handlers translate platform-specific data into Outfound's universal format.

### Workspace Mapping
Outfound maps platform workspaces to Outfound clients, so multi-client agencies can run different clients on different platforms (or the same platform) and see everything unified in Outfound.

---

## Why This Matters

### Platform Freedom
You're not locked in. Switch from Instantly to Smartlead? Your analytics, attribution, and lead database stay intact. Run both simultaneously? Everything shows up in the same dashboard.

**Why it's a game-changer:** Platform lock-in is one of the biggest risks in outbound. Teams accumulate months of data, build processes around one tool, and feel trapped. Outfound breaks the dependency. Your intelligence layer sits above the sending tool, so the sending tool becomes interchangeable.

### Multi-Platform Operations
Many agencies and large teams use multiple sending platforms -- one for high-volume campaigns, another for premium personalized outreach, a third for specific clients. With Outfound, all of these feed into the same system.

### Apples-to-Apples Comparison
Because data is normalized, you can compare campaign performance across platforms. Is your reply rate better on Instantly or Smartlead? Which platform's campaigns generate more attributed meetings? These cross-platform comparisons are impossible without a unified analytics layer.

### Single Source of Truth
Instead of checking three dashboards, pulling three exports, and reconciling data in a spreadsheet, you have one place for everything. One analytics dashboard, one attribution system, one lead database, one inbox.

---

## Onboarding

Each platform integration includes a dedicated onboarding flow:

- **Initial sync** to pull in existing campaign data
- **Sync status tracking** to monitor onboarding progress
- **Platform-specific configuration** for workspace mapping and event filtering

Once onboarded, data flows continuously without manual intervention.

---

## What This Means For Your Team

- **Ops teams** aren't locked into one vendor's ecosystem
- **Agencies** can run different clients on different platforms without fragmented reporting
- **Campaign managers** compare cross-platform performance in one view
- **Leadership** gets unified reporting regardless of the tools being used
- **Procurement teams** can negotiate and switch platforms without losing data
