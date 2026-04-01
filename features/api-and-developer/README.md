# API & Developer Access

### Build on Top of Your Outbound Data

Outfound provides comprehensive API access to your outbound data. Scoped API keys, tiered rate limiting, and full endpoint coverage let developers build custom workflows, dashboards, integrations, and automations on top of the platform.

---

## API Key Management

### Scoped Keys
API keys can be scoped at two levels:

- **Organization-level** -- Access to all data across all clients
- **Client-level** -- Access restricted to a specific client's data

This lets you create keys for different use cases: a broad key for internal tooling, a narrow key for a specific client's integration.

### Multiple Keys
Create as many API keys as you need. Different keys for different systems, team members, or environments. Each key is independently managed and can be revoked without affecting others.

### Key Security
- Keys are hashed on storage -- the full key is only shown once at creation
- Regenerate keys without creating a new one (same ID, new secret)
- Deactivate keys instantly when access should be revoked
- Key prefixes for visual identification

---

## Rate Limiting Tiers

| Tier | Requests/Hour | Best For |
|---|---|---|
| **Basic** | 100 | Light integrations, single-purpose scripts |
| **Standard** | 1,000 | Regular API usage, CRM syncing |
| **Premium** | 10,000 | High-frequency polling, real-time dashboards |
| **Enterprise** | 100,000 | Heavy automation, data pipeline feeds |

Rate limits are per API key, so different keys can have different tiers based on their use case.

---

## What You Can Access

### Campaign Data
- Campaign configurations and metadata
- Campaign status and send statistics
- Sequence and variant details

### Analytics
- Campaign performance metrics (all the same data available in the dashboard)
- Lead category breakdowns
- Attribution analytics
- Email infrastructure metrics
- Mailbox health data

### Inbox
- Email conversations (sent and received)
- Conversation threads and metadata
- Email status filtering

### Attribution
- Attribution event feed
- Grouped attribution data
- Export capabilities

### Lead Database
- People search with filters
- Company search with filters
- Person enrichment by email
- Catalog/dropdown values
- Data exports

### Email Infrastructure
- Bounce tracking and analysis
- Account health metrics

---

## Use Cases

### Custom Dashboards
Build your own reporting interface pulling data from Outfound's API. Create views tailored to your team's specific needs, combine outbound data with data from other systems, or embed metrics in your existing internal tools.

### CRM Enrichment
Pull enrichment data from Outfound's lead database and push it into your CRM (beyond the built-in HubSpot integration). Any CRM that accepts API data can be connected.

### Data Warehouse Feeds
Pull data on a schedule to feed your data warehouse. Combine outbound data with marketing, product, and revenue data for cross-functional analytics.

### Custom Automations
Build triggers and workflows based on outbound events. When combined with the [Webhook Relay](../integrations/webhook-relay.md), you have both push (webhooks) and pull (API) options for automation.

### Client Portals
Agencies can build custom client-facing dashboards using client-scoped API keys. Give clients access to their own data in your branded interface.

### Quality Monitoring
Automated scripts that monitor campaign health, flag anomalies, and alert on issues -- using the API to check metrics programmatically.

---

## Why It Matters

**Why it's a game-changer:** Most outbound tools treat API access as an afterthought -- limited endpoints, no rate limiting tiers, no key scoping. Outfound treats the API as a first-class product. The same data you see in the dashboard is available programmatically, with proper access controls and scale-appropriate rate limits. This turns your outbound platform into a programmable data source that fits into any tech stack.

---

## What This Means For Your Team

- **Developers** get clean, well-structured API access with proper key management
- **Ops teams** can build custom automations and monitoring
- **Data teams** can feed outbound data into warehouses and BI tools
- **Agencies** can build client-facing portals with scoped access
- **Product teams** can embed outbound metrics into internal tools
