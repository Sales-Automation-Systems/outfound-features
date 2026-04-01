# Team & Workspace Management

### Multi-Tenant Workspaces with Granular Permissions

Outfound is built for teams -- from solo operators running one brand to agencies managing dozens of clients. The workspace system provides full data isolation between clients, role-based access control with granular permissions, and a team management layer that scales with your operation.

---

## Organization & Client Structure

### Organizations
An organization is the top-level entity in Outfound. It represents your company or agency. Everything rolls up to the organization: billing, API keys, integrations, and team members.

### Clients (Workspaces)
Within an organization, you create clients -- sometimes called workspaces. Each client represents a separate brand, company, or project you're running outbound for.

**Key properties of clients:**
- **Complete data isolation** -- One client's data is never visible to another client
- **Separate integrations** -- Each client can have its own platform connections, CRM integration, and sending infrastructure
- **Independent analytics** -- All metrics are available per-client, so you can report on each client separately
- **Custom configuration** -- Notification settings, webhook relay, auto-responders, and lead categories are configured per client

**Why it matters for agencies:** You manage 15 clients. Each one has different campaigns, different CRM setups, different Slack channels for notifications. Outfound's client structure means each one is a self-contained workspace, but you have a single organizational view across all of them.

---

## Role-Based Access Control

### Roles

| Role | Description |
|---|---|
| **Agency Admin** | Full access to everything across all clients |
| **Agency User** | Access to assigned clients with standard permissions |
| **Client User** | Access to their own client workspace only |

### Granular Permissions

Permissions are not binary. Each role has specific permissions across different feature areas:

- **Client management** -- Create, edit, delete clients
- **Email campaigns** -- View and manage campaigns
- **Campaign analytics** -- Access to campaign performance data
- **Infrastructure analytics** -- Access to domain and mailbox health
- **Lead category analytics** -- Access to reply classification data
- **Attribution analytics** -- Access to conversion attribution
- **CRM integrations** -- Manage HubSpot and other CRM connections
- **API keys** -- Create and manage API access
- **User management** -- Invite, edit, remove team members
- **Webhook relay** -- Configure event forwarding
- **Auto-responders** -- Set up automatic replies
- **Lead database** -- Access to the lead database and search
- **AI integrations** -- Manage AI provider connections

Each permission can be independently granted or revoked per role.

---

## Team Management

### User Invitations
Invite team members via email. Each invitation includes:
- Role assignment
- Client access assignments (for non-admin roles)
- Invitation acceptance tracking

### Multi-Client Access
Team members can be granted access to specific clients. An SDR working on three clients sees only those three workspaces. An account manager sees only their assigned accounts.

**Why it matters:** Data isolation isn't just between organizations -- it's within them. Team members only see what they need to see. An SDR working on Client A never accidentally accesses Client B's data.

### User Lifecycle
- **Invite** -- Send invitation email
- **Accept** -- User creates account and joins
- **Update** -- Change role or client access
- **Remove** -- Revoke access

---

## Why This Matters for Agencies

Agencies are Outfound's power users, and the workspace system is designed for them:

### Client Isolation
Every client is a sealed workspace. Their data, campaigns, integrations, and analytics are completely separate. There's zero risk of cross-contamination.

### Scalable Operations
Adding a new client is creating a new workspace. The client gets their own analytics, their own integrations, their own notifications -- all managed under your organizational umbrella.

### Team Scaling
As your agency grows, you add team members and assign them to specific clients. Permissions ensure everyone has access to exactly what they need and nothing more.

### Unified Organizational View
While clients are isolated, you as the agency admin see across all of them. Organizational-level analytics, billing, and team management give you the bird's-eye view of your entire operation.

### Client Onboarding
When you onboard a new client, you create their workspace, connect their sending platform, set up their CRM integration, configure their Slack notifications, and assign team members -- all within Outfound. No separate tool setup required.

---

## Why This Matters for Internal Teams

Even if you're not an agency, the workspace system is valuable:

- **Multiple brands** -- Run outbound for different products or business units in separate workspaces
- **Market segments** -- Separate enterprise outbound from SMB outbound for cleaner analytics
- **Experimentation** -- Create a test workspace to experiment without affecting production campaigns
- **Regional operations** -- Separate workspaces for different geographies or teams

---

## What This Means For Your Team

- **Agency owners** get a scalable system that grows with their client base
- **Operations teams** get clean data isolation and organized workspace management
- **Team leads** can assign members to specific clients with appropriate access
- **Compliance teams** get permission-level audit trails
- **New team members** see only what they need from day one
