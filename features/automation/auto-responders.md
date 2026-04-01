# Auto-Responders

### Instant Replies When It Matters Most

Outfound's auto-responder system triggers automatic email responses through your sending infrastructure when specific types of replies come in. When a prospect shows interest, Outfound detects it, classifies it, and dispatches a pre-configured response -- faster than any human could react.

---

## How It Works

### Trigger-Based Responses
Auto-responders are triggered by lead categories. When Outfound classifies an incoming reply into a category you've configured, it dispatches a pre-written response through your sending infrastructure.

**Example:**
- Prospect replies with interest → Auto-responder sends a meeting link and brief intro
- Prospect asks for more information → Auto-responder sends a case study or one-pager
- Prospect says "not now, maybe next quarter" → Auto-responder acknowledges and sets expectations

### Configuration Levels

**Campaign-level:** Set auto-responders for specific campaigns. Different campaigns get different responses based on the offer, audience, or stage.

**Client-level:** Set default auto-responders that apply across all campaigns for a client. Campaign-specific configs override client-level defaults when both exist.

### What You Configure
- **Name** -- Label for internal tracking
- **Target lead categories** -- Which reply types trigger the response
- **Email body** -- The response content (HTML or plain text)
- **Active/inactive toggle** -- Turn auto-responders on and off without deleting them

---

## Why Speed Matters

Research consistently shows that response time is one of the strongest predictors of conversion in outbound sales:

- Responding within 5 minutes = dramatically higher meeting book rate
- Responding within 1 hour = still strong
- Responding next day = prospect has gone cold

Auto-responders ensure that every positive reply gets an immediate acknowledgment, even if your SDR is in a meeting, asleep, or handling another prospect.

**Why it's a game-changer:** The gap between "prospect expressed interest" and "team member responds" is where deals die. Auto-responders close that gap to zero. The prospect feels heard immediately, and your SDR follows up personally when they're available -- but the momentum was never lost.

---

## Smart Processing

### Event-Driven
Auto-responders are processed through an event-driven system. When a prospect event occurs:

1. The event is matched against active auto-responder configurations
2. Matching checks campaign ID, lead category, and active status
3. Qualified responses are queued in an outbox
4. Responses are sent in order, preventing duplicates

### Billing-Aware
Auto-responders only fire when your organization's billing status is current. This prevents unexpected responses during account issues.

### Priority Resolution
When both a campaign-level and client-level config match the same event, the campaign-specific configuration takes priority. This gives you fine-grained control without conflicts.

---

## Use Cases

### Immediate Meeting Link
When a prospect says they're interested, auto-respond with your Calendly/scheduling link. By the time your SDR sees the notification, the meeting might already be booked.

### Information Delivery
When a prospect asks "tell me more," auto-respond with a brief overview and a link to relevant content. The prospect gets value immediately instead of waiting.

### Acknowledgment
Even a simple "Thanks for your reply! Someone from our team will follow up within the hour" sets expectations and keeps the prospect warm.

### Out-of-Office Handling
When a prospect sends an out-of-office reply, auto-respond with a note to reconnect when they're back. Keeps the thread alive without annoying the prospect.

---

## What This Means For Your Team

- **SDRs** never miss the critical first response window
- **Campaign managers** can build response workflows without involving engineering
- **Sales managers** see improved meeting book rates from faster response times
- **Prospects** get a better experience with immediate, relevant responses
