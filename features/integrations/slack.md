# Slack Notifications

### Real-Time Alerts When Prospects Engage

Outfound sends real-time notifications to your Slack workspace when important things happen in your outbound campaigns. Positive replies, meeting bookings, conversions -- your team sees them the moment they happen, in the channels where they already work.

---

## What Gets Notified

Notifications are triggered by prospect events -- specifically, lead category changes. This means you control exactly what generates a Slack notification:

- **Positive reply received** -- A prospect expressed interest
- **Meeting booked** -- A prospect scheduled a call
- **Deal closed** -- A prospect converted to a customer
- **Custom categories** -- Any lead category you've defined

Each notification includes rich context:
- Lead category (what happened)
- Campaign name (which campaign)
- Prospect email, name, and details
- Company name, job title, website, LinkedIn
- Preview of the conversation content
- Enrichment data from the lead database

---

## Configuration

### Channel Routing
Point notifications to specific Slack channels. Different channels for different event types is common:

- `#outbound-wins` for positive replies and meetings
- `#outbound-alerts` for all campaign activity
- `#client-name` for client-specific notifications

### Category Filtering
Select which lead categories trigger notifications. Get alerts for the events that matter and filter out the noise.

### Custom Bot Appearance
Customize the Outfound bot's name and icon in Slack to match your team's preferences.

### Per-Client Configuration
Set up different notification rules for different clients. Agency teams can route each client's notifications to the appropriate channel with the appropriate filters.

---

## Why It Matters

### Speed to Response
When a prospect replies positively to a cold email, the clock starts ticking. Every minute between their reply and your follow-up reduces the chance of booking a meeting. Slack notifications eliminate the delay between "prospect replied" and "team is aware."

**Why it's a game-changer:** Your SDRs don't need to check their sending platform every 10 minutes looking for replies. The notification comes to them, in Slack, the moment it happens. This can cut response time from hours to minutes.

### Team Visibility
Everyone who needs to know about outbound activity sees it in real time. Sales managers see pipeline building. AEs see warm leads coming in. Leadership sees the outbound machine working.

### Celebration and Momentum
There's something powerful about seeing a `#outbound-wins` channel light up with positive replies and booked meetings. It builds team momentum, highlights what's working, and keeps outbound top of mind across the organization.

---

## How It Works

### OAuth Installation
One-click Slack installation through OAuth. Authorize the Outfound bot, select your workspace, and you're connected.

### Automatic Processing
Every 3 minutes, Outfound scans for new prospect events that match notification configurations. Matching events are queued and sent to Slack in order, ensuring reliable delivery without flooding.

### Resilient Delivery
Notifications use an outbox pattern -- events are queued, sent, and confirmed. If Slack is temporarily unavailable, notifications are retried automatically. Nothing gets lost.

### Auto-Rejoin
If the Outfound bot is removed from a channel and later re-added, it automatically rejoins and resumes notifications without reconfiguration.

---

## What This Means For Your Team

- **SDRs** respond to hot leads within minutes instead of hours
- **Sales managers** get real-time visibility into pipeline generation
- **Account executives** see warm leads the moment they qualify
- **Leadership** sees outbound results flowing through the organization
- **The whole team** shares in the wins and builds momentum
