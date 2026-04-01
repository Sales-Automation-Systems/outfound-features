# Webhook Relay

### Forward Any Event to Any System

Outfound's webhook relay lets you push real-time events from your outbound operation to any external system. Campaign activity, attribution events, lead category changes -- route them to your internal tools, Zapier, Make.com, custom APIs, or data warehouses. If a system can receive an HTTP POST, Outfound can send it data.

---

## What Events Can Be Relayed

### Campaign Events
- **Email sent** -- An email was delivered to a prospect
- **Reply received** -- A prospect replied
- **Auto-reply received** -- An automated response was detected
- **Email bounced** -- An email failed to deliver

### Attribution Events
- **Sign-up** -- A prospect signed up for your product
- **Meeting booked** -- A prospect scheduled a meeting
- **Paying customer** -- A prospect became a paying customer
- **Website visit** -- A tracked website visit occurred
- **Custom events** -- Any custom conversion event you've defined

### Lead Category Events
Dynamic events based on your configured lead categories. When a prospect is classified into a specific category (interested, not interested, meeting booked, etc.), a webhook fires.

---

## Configuration

### Organization-Level Webhooks
Set up webhooks that apply across your entire organization. Every client's events are forwarded to the same endpoints.

### Client-Level Webhooks
Override or extend organization-level settings for specific clients. Route one client's events to their own endpoint while keeping the default for everyone else.

### Scope Merging
Client-level configurations intelligently merge with organization-level settings. You set the defaults at the org level and customize per client only where needed.

### Multiple Endpoints
Configure multiple destination URLs per event type. Useful for:
- Sending to both a primary and backup system
- Feeding multiple downstream tools simultaneously
- Routing to different environments (staging vs. production)

### Custom Headers
Add custom HTTP headers to webhook requests. Useful for API key authentication, custom routing, or any header-based configuration your receiving system needs.

### Active/Inactive Toggle
Enable or disable webhooks without deleting the configuration. Pause relaying during maintenance or testing without losing your setup.

---

## Testing

Outfound includes built-in webhook testing:

- **Send test payload** to any configured endpoint
- **Measure response time** to verify endpoint performance
- **Validate connectivity** before going live

No more "configure and pray." Test your webhooks before activating them to ensure the receiving system handles the payload correctly.

---

## Use Cases

### Feed Data to Your Data Warehouse
Send every outbound event to BigQuery, Snowflake, or Redshift for custom analytics beyond what Outfound provides.

### Trigger Zapier/Make Workflows
Connect outbound events to any of the thousands of apps in Zapier or Make.com. When a prospect replies, trigger a Slack notification, update a Google Sheet, create a task in Asana, or enrich the contact in Clearbit.

### Custom Internal Tools
Forward events to your own APIs for custom processing -- lead scoring, routing, enrichment, or any internal workflow.

### Multi-System Sync
Keep multiple systems in sync without building custom integrations. The webhook relay handles the data flow; your receiving systems handle the logic.

### Client Reporting
Agencies can forward client-specific events to client-owned systems, giving clients direct access to their outbound data in their own tools.

---

## Why It Matters

**Why it's a game-changer:** Most outbound tools are closed systems. Your data goes in, and maybe you can export a CSV. Outfound's webhook relay makes your outbound data available to your entire tech stack in real time. Every event, every conversion, every reply -- flowing to wherever you need it, the moment it happens.

This turns Outfound from a standalone tool into the hub of your outbound tech stack.

---

## What This Means For Your Team

- **Ops teams** can build custom automations without writing code
- **Data teams** get real-time event streams for warehousing
- **Agencies** can route data to client systems with per-client configuration
- **Developers** can build custom integrations against a reliable event stream
- **Marketing teams** can trigger multi-channel follow-ups based on outbound events
