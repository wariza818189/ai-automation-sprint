# AI Automation Sprint

A 90-day practical journey focused on building AI automations, solving business problems, creating portfolio proof, and developing client-ready skills.

## Mission

**Business Problem → Automation → Working Proof → Portfolio → Client**

The goal is not to learn every automation tool.

The goal is to become capable of identifying a business problem, building an automation that solves it, documenting the result, demonstrating it, and eventually delivering it as a service.

## Learning Philosophy

**20% Learn · 80% Build**

Avoid tutorial hell.

Learn only what is necessary for the current task, then apply it immediately.

## Learning Loop

**Understand → Observe → Predict → Learn → Code/Build → Run → Debug → Review → Rebuild → Apply**

## Reforged Roadmap

### Month 1 — Foundation + First Workflow

#### Week 1 — n8n Core + Deployment

Focus:

- [ ] Triggers
- [ ] Nodes
- [ ] Inputs / Outputs
- [ ] Connections
- [ ] Data Mapping
- [ ] Expressions
- [ ] Webhooks
- [ ] HTTP Requests
- [ ] Workflow Execution
- [ ] Basic deployment concepts
- [ ] n8n Cloud
- [ ] Self-hosting concepts
- [ ] Environment variables
- [ ] Credentials / secrets

Build progressively:

1. Manual Trigger → data
2. Webhook → response
3. Webhook → transformation → response
4. Webhook → HTTP Request → response

Deployment goal:

- [ ] Understand local vs hosted n8n
- [ ] Understand how a 24/7 workflow is deployed
- [ ] Deploy one working workflow using an appropriate hosting option

---

#### Week 2 — OpenAI API + AI Lead Enrichment

Focus:

- [ ] API requests
- [ ] Authentication
- [ ] Prompt / instructions
- [ ] Structured JSON
- [ ] Schema thinking
- [ ] Function / tool calling
- [ ] Error handling

Build Portfolio Project 1:

**AI Lead Enrichment & Personalized Outreach**

Concept:

Lead source / authorized data
→ n8n
→ AI profile analysis
→ personalized message
→ review / approval
→ email sending
→ logging

Important:

Use lawful and authorized data sources and respect the terms and privacy requirements of the platforms and services involved.

Deliverables:

- [ ] workflow.json
- [ ] README
- [ ] Architecture explanation
- [ ] Screenshots
- [ ] Loom demo
- [ ] Test data
- [ ] Setup instructions

---

#### Week 3 — GoHighLevel + Loom Strike

Focus:

- [ ] Sub-accounts
- [ ] Contacts
- [ ] Custom fields
- [ ] Tags
- [ ] Pipelines
- [ ] Opportunities
- [ ] Workflows
- [ ] Forms
- [ ] Email / SMS actions
- [ ] Basic integrations

Build:

**CSV / Form → GHL Contact → Tag → Pipeline → Follow-up**

Client acquisition preparation:

- [ ] Choose one target niche
- [ ] Identify real business problems
- [ ] Build a relevant demo
- [ ] Record a 1–2 minute personalized Loom
- [ ] Explain the problem
- [ ] Show the automation
- [ ] Show the expected outcome

Core principle:

**Show the steel. Don't just describe it.**

---

#### Week 4 — Beta Pilot + Case Study

The immediate goal is not to assume a paying client is guaranteed.

The target is:

**First Beta Pilot**

Build and test an automation with a real business or realistic pilot environment.

Possible offer:

- Free pilot
- Discounted pilot
- Limited-scope pilot

In exchange for appropriate permission to collect:

- [ ] Feedback
- [ ] Testimonial
- [ ] Case study
- [ ] Performance evidence

### Important ROI Rule

Never present simulated or estimated results as real client results.

Use labels such as:

- Target
- Estimated
- Simulated

Use measured results only when actual data exists.

---

# Month 2 — Portfolio + Client Acquisition

## Week 5 — Portfolio Project 2

Build:

**Appointment Reminder Automation**

Form
→ n8n
→ CRM
→ SMS / WhatsApp
→ Logging

Deliver:

- [ ] Workflow
- [ ] Documentation
- [ ] Screenshots
- [ ] Loom demo
- [ ] Test evidence

---

## Week 6 — Portfolio Project 3

Build:

**Invoice / Receipt Automation**

Google Form
→ n8n
→ AI extraction
→ PDF
→ Email
→ CRM / Log

Deliver:

- [ ] Workflow
- [ ] Documentation
- [ ] Screenshots
- [ ] Loom demo
- [ ] Test evidence

---

## Week 7 — Client Acquisition Setup

Prepare:

- [ ] Upwork
- [ ] OnlineJobs PH
- [ ] Fiverr
- [ ] LinkedIn
- [ ] Notion portfolio
- [ ] Carrd
- [ ] Loom
- [ ] Proposal template
- [ ] Discovery questions

Portfolio messaging:

**Problem → Automation → Outcome → Proof**

---

## Week 8 — Outreach Blitz

Start targeted outreach.

Track:

- [ ] Messages sent
- [ ] Replies
- [ ] Calls
- [ ] Qualified opportunities
- [ ] Proposals
- [ ] Wins
- [ ] Losses
- [ ] Rejection reasons

Prefer personalized outreach over generic spam.

Loom-first outreach is encouraged when a short demonstration can communicate the solution better than text alone.

---

# Month 3 — Delivery + Retention

## Weeks 9–10 — Client Delivery

Process:

**Understand Problem → Confirm Scope → Build → Test → Document → Demo → Deliver → Support**

---

## Week 11 — Retention

Explore recurring services based on actual client needs:

- [ ] Maintenance
- [ ] Monitoring
- [ ] Small workflow changes
- [ ] Reporting
- [ ] Support
- [ ] Retainer offer

---

## Week 12 — Systematize

Create reusable systems:

- [ ] Proposal template
- [ ] Discovery checklist
- [ ] Client onboarding
- [ ] Testing checklist
- [ ] Delivery checklist
- [ ] Handover document
- [ ] Support SOP
- [ ] Retainer process

---

# Daily Accountability

Every meaningful learning session should leave evidence.

1. Define the objective.
2. Learn the required concept.
3. Build.
4. Run.
5. Debug.
6. Review.
7. Record progress.
8. Commit meaningful work.
9. Push to GitHub.

## GitHub Evidence

Examples:

- `Add n8n webhook exercise`
- `Document n8n expressions`
- `Add lead enrichment workflow`
- `Add deployment notes`
- `Record beta pilot results`

Do not create fake progress commits.

---

# Current Focus

**Week 1 — n8n Core + Deployment**

The immediate goal is to understand n8n workflows, build basic automations, and understand how a workflow moves from local development to a reliable hosted environment.

---

# Repository Structure

```text
ai-automation-sprint/
├── AGENTS.md
├── BOOTCAMP.md
├── README.md
├── progress/
├── notes/
├── exercises/
└── projects/