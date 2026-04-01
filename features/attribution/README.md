# Attribution

### Know Exactly Which Emails Drive Revenue

Attribution is what separates Outfound from every other outbound tool. While other platforms stop at "email sent, reply received," Outfound traces the full journey from first email to signed deal. It answers the question that every outbound team struggles with: **which campaigns, which emails, which copy actually generated revenue?**

---

## How Attribution Works

### Event Tracking
Outfound tracks conversion events across your pipeline:

- **Sign-ups** -- New accounts created
- **Meetings booked** -- Calendar events scheduled
- **Paying customers** -- Deals closed, revenue generated
- **Website visits** -- Tracked visits to your site
- **Custom events** -- Any conversion milestone you define

Events can arrive from multiple sources: your CRM (HubSpot), webhook integrations, or custom event tracking.

### Intelligent Prospect Linking

When a conversion event comes in, Outfound automatically links it back to the prospect who received your outbound emails. The linking system uses two methods:

**Hard linking (exact match):** The conversion email matches an email in your prospect database. This is a definitive attribution.

**Soft linking (domain match):** The conversion comes from the same company domain as a prospect you emailed. Someone at the company converted, even if it wasn't the exact person you reached out to. This captures the reality that outbound often influences buying decisions at the company level, not just the individual level.

### Chronology Enforcement
Attribution only counts if the conversion happened *after* the first email was sent. If someone signed up before you ever emailed them, Outfound won't take credit. This prevents false positions and keeps your attribution data honest.

### Common Domain Exclusion
Free email domains (gmail.com, outlook.com, etc.) are automatically excluded from soft linking. This prevents wildly inaccurate domain-level attribution across unrelated people who happen to use the same email provider.

---

## Attribution Feed

The attribution feed gives you a real-time stream of every conversion event with full context:

- **Event type** -- What happened (sign-up, meeting, deal, etc.)
- **Event time** -- When it happened
- **Prospect details** -- Who was contacted
- **Campaign info** -- Which campaign reached them
- **Linking type** -- Hard link (exact) or soft link (domain)
- **Time from first email** -- Days between first contact and conversion
- **Paying customer status** -- Whether they've become revenue

The feed supports:
- **Cursor-based pagination** for navigating large datasets
- **Filtering** by event type, date range, client, campaign
- **Grouped views** by company domain with aggregate metrics
- **CSV export** for reporting and analysis

---

## CRM Deal Attribution

When connected to HubSpot, attribution becomes even more powerful:

- **Deal tracking** -- See which CRM deals originated from outbound campaigns
- **Deal stage mapping** -- Track deals through your pipeline stages
- **Revenue attribution** -- Connect closed-won revenue directly to the campaigns that generated it
- **Outcome history** -- Full timeline of deal progression

**Why it's a game-changer:** For the first time, you can walk into a board meeting and say "Campaign X generated $Y in pipeline and $Z in closed revenue" with data to back it up. This isn't estimated or modeled -- it's tracked at the event level and linked to real CRM deals.

---

## Attribution KPIs

Outfound calculates key attribution metrics automatically:

| KPI | Description |
|---|---|
| **Attributed conversions** | Events successfully linked to outbound prospects |
| **Unmatched events** | Conversion events that couldn't be linked (data quality signal) |
| **Attribution rate** | Percentage of events that could be linked |
| **Average days to convert** | Time from first email to conversion event |

These KPIs give you a health check on your attribution system itself. A high unmatched rate might mean you're sending from platforms that don't share prospect data, or that your CRM data isn't flowing correctly.

---

## Attribution Time Series

View attribution events over time to understand:
- **Conversion velocity** -- Are deals accelerating or slowing?
- **Linked vs. unlinked trends** -- Is your data matching improving?
- **Seasonal patterns** -- When do conversions spike?
- **Campaign impact windows** -- How long after launch do campaigns generate conversions?

---

## Appeal System

Sometimes attribution gets it wrong. A "positive reply" might actually be an auto-responder. A "meeting booked" might be a false positive. Outfound includes a built-in appeal system for disputed attributions:

### How Appeals Work
1. A team member flags a questionable attribution
2. They select a reason category:
   - **Not interested** -- Prospect was never genuinely interested
   - **Automated response** -- Out-of-office, bounce, or delivery failure
   - **Targeting error** -- Wrong person, wrong company, doesn't fit ICP
   - **AI misclassified** -- AI incorrectly labeled this as positive
   - **Other** -- Free-text explanation
3. An admin reviews the appeal
4. The attribution is confirmed, approved (removed), or rejected (kept)

### Why It Matters
No attribution system is perfect. The appeal mechanism lets your team correct errors, improve data quality, and build trust in the numbers. Over time, appeal patterns also reveal systematic issues -- if you're seeing lots of "AI misclassified" appeals, the classification model needs tuning. If you're seeing "targeting errors," your ICP definitions need work.

**Why it's a game-changer:** Most tools don't have attribution at all. The ones that do treat it as a black box. Outfound's appeal system makes attribution a collaborative, improvable process -- not a number you have to accept blindly.

---

## What This Means For Your Team

- **Leadership** can tie outbound spend directly to revenue for the first time
- **Campaign managers** know which campaigns actually generate pipeline, not just replies
- **Sales teams** see the outbound touchpoints that preceded every deal
- **Finance teams** get real ROI data for outbound investment decisions
- **Ops teams** can audit and correct attribution through the appeal system
