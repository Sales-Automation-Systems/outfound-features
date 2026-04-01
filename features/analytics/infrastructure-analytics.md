# Infrastructure Analytics

### Domain & Mailbox Health at a Glance

Your sending infrastructure is the foundation of your entire outbound operation. If your domains are burned, your accounts are throttled, or your bounce rates are climbing, nothing else matters. Outfound gives you complete visibility into the health of every domain, every email account, and every provider in your portfolio -- in real time.

---

## What's Monitored

### Domain-Level Metrics
- **Sending volume per domain** -- How many emails each domain is pushing
- **Bounce rates per domain** -- Track domain reputation through bounce patterns
- **Reply rates per domain** -- See which domains are landing in inboxes vs. spam
- **Domain reputation trending** -- Is domain health improving or degrading over time?

### Email Account Metrics
- **Sent count per account** -- Daily volume per mailbox
- **Bounce count per account** -- Identify accounts with deliverability issues
- **Reply count per account** -- See which accounts are performing well
- **Disconnection count** -- Track accounts that go offline or lose authentication
- **Account status events** -- Monitor reconnections, failures, and state changes

### Provider-Level Metrics
- **Distribution by provider** -- See your account split across Gmail, Outlook, and others
- **Performance by provider** -- Compare bounce and reply rates across providers
- **Disconnection trends by provider** -- Identify provider-specific issues early

### Capacity Metrics
- **Daily sending capacity** -- Total available sends across all accounts
- **Capacity utilization** -- How much of your available capacity you're actually using
- **Active inbox count** -- Number of accounts actively sending

---

## Time-Series Monitoring

Every infrastructure metric is available as a time series:

- **Daily granularity** with optional weekend filtering
- **Trend lines** showing whether metrics are improving or declining
- **Period-over-period comparison** (e.g., this week vs. last week)
- **Custom date ranges** for any analysis window

**Why it matters:** A single bad day doesn't tell you much. A three-week decline in reply rates across one provider tells you something systemic is happening. Time-series monitoring turns noise into signal.

---

## Bounce Analysis

Outfound tracks every bounce with detailed information:

- **Bounce type** -- Hard bounce (invalid address) vs. soft bounce (temporary issue)
- **Failure reasons** -- The actual error message from the receiving server
- **Bounce rate per account** -- Identify which accounts are most affected
- **Bounce trending** -- Catch reputation issues before they become critical

**Why it's a game-changer:** Most tools tell you "X emails bounced." Outfound tells you *why* they bounced, *which accounts* are affected, and whether the problem is *getting worse*. This is the difference between reacting to deliverability crises and preventing them.

---

## Sending Capacity Dashboard

Know exactly how much runway your infrastructure has:

- **Total daily capacity** across all connected accounts
- **Current utilization** as a percentage
- **Per-account capacity** with individual limits
- **Capacity growth tracking** as you add new accounts

**Why it matters:** Running at 95% capacity is a risk. Running at 30% is waste. The capacity dashboard helps you right-size your infrastructure to match your campaign volume.

---

## DNC & Blacklist Management

Outfound includes built-in DNC (Do Not Contact) list management:

- **Batch upload** DNC lists to prevent sending to specific addresses or domains
- **Blacklist enforcement** across all campaigns automatically
- **DNC tracking** in the inbox -- emails to DNC contacts are flagged

**Why it matters:** Compliance isn't optional. One email to a DNC contact can create legal liability. Outfound enforces your DNC lists at the infrastructure level, so you never accidentally contact someone who shouldn't be contacted.

---

## What This Means For Your Team

- **Deliverability specialists** get a single dashboard for the entire infrastructure
- **Ops teams** can monitor capacity and plan account provisioning
- **Campaign managers** can identify infrastructure-related performance issues
- **Compliance teams** can manage DNC lists and audit sending behavior
