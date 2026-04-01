# Mailbox Health Scoring

### Per-Account Health Intelligence with Portfolio Benchmarking

Outfound doesn't just tell you how your campaigns are performing -- it tells you how every single email account in your portfolio is performing, scored against your own benchmarks, with trend analysis across multiple time windows.

---

## Per-Mailbox Metrics

Every email account connected to Outfound gets its own health profile with:

### Raw Performance
- **Sent count** -- Total emails sent from this account
- **Reply count** -- Replies received to emails from this account
- **Bounce count** -- Bounces on emails from this account
- **Disconnection count** -- How many times this account has gone offline

### Sentiment Breakdown
- **Positive human replies** -- Genuine interest
- **Negative human replies** -- Rejections
- **Neutral human replies** -- Ambiguous responses
- **Bot replies** -- Automated responses

### Derived Rates
- **Reply rate** -- Replies / sent (with human vs. bot breakdown)
- **Bounce rate** -- Bounces / sent
- **Sentiment distribution** -- Percentage breakdown of reply types

---

## Multi-Window Analysis

Every metric is calculated across four time periods simultaneously:

| Window | Purpose |
|---|---|
| **Last 7 days** | Current performance snapshot |
| **Last 30 days** | Short-term trend |
| **Last 90 days** | Medium-term health |
| **All-time** | Historical baseline |

**Period-over-period differentials** show whether each metric is improving or declining. A mailbox with a 3% reply rate in the last 7 days vs. 5% over 30 days is trending down -- and you see that immediately.

**Why it matters:** A single snapshot doesn't tell you if an account is healthy or sick. Multi-window analysis gives you the trajectory. You can catch declining accounts before they affect campaign performance.

---

## Health Scoring System

Outfound calculates a composite health score for each mailbox based on:

### Reply Rate Health
Your account's reply rate compared to:
- **Organization bucket average** -- How you compare to your own portfolio
- **Client bucket average** -- How accounts for the same client compare
- **Platform bucket average** -- How accounts on the same email provider compare

### Bounce Rate Health
Trend-based scoring that flags accounts with rising bounce rates before they become critical.

### Disconnection Health
Tracks account stability -- frequent disconnections indicate authentication issues or account health problems.

### Overall Health Score
A composite score combining all factors into a single health indicator. Instantly see which accounts need attention.

**Why it's a game-changer:** Other tools show you aggregate campaign metrics. Outfound shows you health *per mailbox* with context. If one account in your portfolio is dragging down a campaign, you see it immediately. If a specific provider is underperforming, you see it in the comparisons. This is the level of visibility that separates amateur outbound operations from professional ones.

---

## Portfolio-Level Benchmarking

The health scoring system uses percentile benchmarks from your own data:

- **P25** -- 25th percentile (bottom quarter of your accounts)
- **Median** -- Your typical account performance
- **P75** -- 75th percentile (your top-performing accounts)

Every account is positioned within these benchmarks. You instantly know whether a mailbox is in your bottom quartile or top quartile, across every metric.

**Why it matters:** "Is a 4% reply rate good for this account?" depends entirely on what's normal for your portfolio. Outfound answers that question automatically with your own data as the benchmark.

---

## What This Means For Your Team

- **Deliverability specialists** can monitor every account individually and spot trouble early
- **Ops teams** can make data-driven decisions about account provisioning and retirement
- **Campaign managers** can route campaigns through their healthiest accounts
- **Agencies** can demonstrate infrastructure quality to clients with per-account data
