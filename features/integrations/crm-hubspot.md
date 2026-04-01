# CRM Integration -- HubSpot

### Your CRM Stays in Sync, Automatically

Outfound's HubSpot integration isn't a basic contact export. It's a deep, bidirectional sync that pushes prospect events, email conversations, and deal outcomes between your outbound operation and your CRM -- automatically, continuously, and without manual data entry.

---

## What Syncs to HubSpot

### Contact Syncing
When a prospect triggers a qualifying event (based on your configured lead categories), Outfound automatically:

- Creates or updates the contact in HubSpot
- Populates contact properties (first name, last name, company, job title, website, LinkedIn)
- Maps lead categories to HubSpot properties

**Why it matters:** SDRs shouldn't be copy-pasting contact info from their sending platform into the CRM. Outfound handles this automatically, ensuring every qualified lead appears in HubSpot with full context -- the moment they qualify.

### Email Conversation Syncing
Outfound logs email conversations directly into HubSpot:

- Outbound emails sent to prospects
- Reply content and metadata
- Email subjects and timestamps

This creates a complete communication history in your CRM without any manual forwarding or BCC workflows.

**Why it matters:** When a sales rep picks up a lead, they see the full email conversation history right in HubSpot. They know what was said, when it was said, and how the prospect responded. No context is lost in the handoff from outbound to sales.

### Deal Attribution
When connected to both HubSpot and Outfound's [attribution system](../attribution/README.md):

- Attribution events are linked to CRM deals
- Deal stage progression is tracked
- Revenue from closed deals is attributed back to the campaigns that generated them
- Deal outcomes are synced for reporting

**Why it's a game-changer:** For the first time, you can see a straight line from "Campaign X sent 500 emails" to "Deal Y closed for $50K" with every touchpoint in between. This is real revenue attribution, not estimated.

---

## How It Works

### OAuth Connection
Connect HubSpot through a standard OAuth flow -- click connect, authorize, done. No API keys to copy, no webhook URLs to configure.

### Event Filtering
You choose which lead categories trigger a CRM sync. Not every reply needs to go to HubSpot -- only the ones that matter:

- Interested replies? Sync.
- Meeting booked? Sync.
- Out-of-office auto-reply? Skip.
- Not interested? Your choice.

This keeps your CRM clean and prevents it from being flooded with noise.

### Automatic Token Management
Outfound automatically refreshes HubSpot authentication tokens before they expire. No more broken integrations because a token timed out. The system checks token expiry every few minutes and refreshes proactively.

### Billing-Aware Processing
CRM syncing only runs when your organization's billing status is current. This prevents sync issues and ensures a clean cutoff if an account lapses.

---

## What Flows Where

```
Outfound → HubSpot
├── Contact data (on qualifying events)
├── Email conversations (sent + received)
├── Lead category mappings
└── Attribution event context

HubSpot → Outfound
├── Deal stage updates
├── Deal outcomes (closed-won/lost)
└── Revenue data for attribution
```

---

## Why This Matters for Outbound Teams

### No More Manual CRM Entry
The #1 reason CRMs have bad data is that salespeople don't want to enter it. Outfound eliminates this by automatically populating contacts and conversations. Your CRM data quality improves without anyone changing their behavior.

### Clean Handoffs
When an SDR generates a qualified lead through outbound, the sales rep who picks it up sees everything in HubSpot: the campaign, the email chain, the prospect's response, and the lead category. The handoff is seamless.

### Revenue Reporting
With deal attribution flowing back from HubSpot, leadership can finally answer: "What is our outbound ROI?" Not estimated, not modeled -- real deal data connected to real campaign activity.

### Audit Trail
Every sync is logged. Every contact push, email log, and deal connection is tracked. If something looks off, you can trace exactly what happened and when.

---

## What This Means For Your Team

- **SDRs** never have to manually enter outbound leads into the CRM
- **Sales reps** get full conversation context when they pick up a lead
- **Sales managers** see pipeline attribution to outbound campaigns
- **Revenue ops** gets clean, automated data flow between outbound and CRM
- **Leadership** gets real ROI numbers for outbound investment
