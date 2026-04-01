# AI Data Agent (MCP)

### Talk to Your Outbound Data in Natural Language

This is Outfound's most innovative feature. The AI Data Agent connects any AI assistant -- ChatGPT, Claude, custom agents -- directly to your outbound analytics warehouse. Ask questions in plain English, and the AI writes and executes analytical queries against your real data in real time.

No dashboards to navigate. No filters to configure. No SQL to write. Just ask.

---

## What It Does

Outfound exposes a Model Context Protocol (MCP) server -- a standardized way for AI agents to access external data. When you connect your AI assistant to Outfound's MCP server, it gains the ability to:

- **Query campaign performance** -- "What's our reply rate by campaign this month?"
- **Analyze attribution** -- "Which campaigns generated the most meetings in Q1?"
- **Check infrastructure health** -- "Which email providers have the highest bounce rates?"
- **Explore copy patterns** -- "Do emails with question subject lines get more replies?"
- **Dive into trends** -- "Show me weekly reply rates over the last 6 months"
- **Cross-reference dimensions** -- "What's the positive reply rate for enterprise prospects vs SMBs?"

The AI agent has access to 20+ data tables spanning campaigns, prospects, conversations, bounces, attribution events, mailbox health, sequence tags, and more.

---

## How It Works

### Guided Discovery
The MCP server doesn't just expose raw data -- it guides the AI through a structured workflow:

1. **Schema discovery** -- The AI first learns what tables and columns exist
2. **Column-level detail** -- It then inspects specific tables to understand exact field names, types, and relationships
3. **Cost estimation** -- Before running a query, the AI estimates how expensive it will be
4. **Query execution** -- The AI writes and runs analytical queries
5. **Iteration** -- If the first query doesn't answer the question, the AI refines and retries

This guided approach means the AI doesn't hallucinate column names or write bad queries. It's forced to discover the actual schema before writing anything.

### Curated Query Examples
The MCP server includes 25+ hand-written query examples organized by intent:
- Campaign performance patterns
- Attribution analysis patterns
- Infrastructure monitoring patterns
- Sequence tag / copy analysis patterns

These examples teach the AI the correct way to query Outfound's data model, so even complex analytical questions get accurate answers.

---

## Why This Is a Game-Changer

### Democratized Data Access
Today, getting answers from outbound data requires either:
1. A data analyst who can write SQL
2. A dashboard that happens to show what you need
3. Exporting to a spreadsheet and doing the analysis manually

The AI Data Agent eliminates all three bottlenecks. Anyone on the team -- from the CEO to a new SDR -- can ask a question and get an answer. No SQL skills needed. No waiting for a data team ticket. No pre-built dashboards required.

### Questions You Didn't Know to Ask
Dashboards only show what they were designed to show. The AI Data Agent can answer questions nobody anticipated:

- "What's the average time between first email and meeting booked for enterprise companies?"
- "Which campaigns have a bounce rate above 5% but still have positive reply rates above 3%?"
- "Show me the top 10 companies by total attribution events, and which campaigns touched them"
- "Compare performance of emails sent on Tuesdays vs Thursdays over the last quarter"

These are real analytical questions that would take hours to answer manually but seconds through the AI agent.

### Real-Time, Not Stale
The AI queries against a real-time analytics warehouse that refreshes every few minutes. You're not looking at yesterday's data -- you're looking at what's happening now.

### Secure by Design
Even though the AI can query freely, the security model is fortress-grade:

- **Tenant isolation** -- Every query is automatically filtered to only return your organization's data. The AI cannot see other customers' data, period.
- **Read-only access** -- The AI can only SELECT data. It cannot modify, delete, or create anything.
- **Dangerous function blocking** -- 30+ dangerous SQL functions are blocked, preventing any attempt at data exfiltration or system manipulation.
- **Resource limits** -- Queries are capped at 10,000 rows and 60-second timeouts, preventing runaway analysis.
- **API key authentication** -- Every request is authenticated with your organization's API key.

---

## What You Can Explore

### Campaign Performance
- Daily/weekly/monthly metrics (sent, replied, bounced, opened)
- Per-client and per-campaign summaries
- A/B variant performance comparisons
- Multi-window analysis (1d/3d/7d/30d rolling)
- Baseline percentile comparisons

### Attribution & Revenue
- Full attribution event history
- Company-level conversion analysis
- Linked vs. unlinked event tracking
- Attribution KPIs (rate, avg days to convert)
- Revenue attribution by campaign

### Infrastructure Health
- Email account distribution by provider
- Sending capacity vs. utilization
- Bounce rate trends by account and provider
- Disconnection monitoring
- Daily active inbox counts

### Copy & Content Analysis
- Tag dimension performance correlation
- Subject line style vs. reply rates
- CTA type vs. conversion rates
- Tone analysis across campaigns
- Structural element comparisons

### Lead & Prospect Data
- Prospect-level activity history
- Email conversation timelines
- Lead category distributions
- Company-level engagement summaries

---

## Supported AI Platforms

The MCP server works with any AI platform that supports the Model Context Protocol:

- **Claude** (Anthropic) -- Native MCP support
- **ChatGPT** (OpenAI) -- Via MCP client
- **Custom AI agents** -- Any agent that can call MCP tools
- **Internal tools** -- Build your own data exploration interface

The server supports both HTTP transport (for production/remote use) and stdio transport (for local development and testing).

---

## What This Means For Your Team

- **Leadership** can get answers to strategic questions without waiting for reports
- **Campaign managers** can explore performance patterns through conversation
- **Sales teams** can ask about prospect activity and pipeline status
- **Data teams** can use the AI as a query assistant for complex analysis
- **Anyone** can become a data analyst by simply asking questions
