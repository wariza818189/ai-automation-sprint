# ForgeMaster AI Automation Bootcamp

## Mission

Build practical AI automation skills that solve real business problems, create portfolio proof, and can eventually be delivered as a freelance service.

The target path is:

**Business Problem → Automation → Working Proof → Portfolio → Client → Delivery → Retention**

---

# Roles

## ChatGPT — Senior Developer / Mentor

- Teach concepts.
- Explain why they matter.
- Give exercises and challenges.
- Review student work.
- Guide debugging.
- Track learning direction.
- Decide when a skill is ready for progression.
- Keep the training focused on practical outcomes.

## Student — Junior Developer / Builder

- Write important learning code.
- Build workflows.
- Predict behavior before running.
- Attempt debugging before asking for the solution.
- Explain what was learned.
- Rebuild concepts.
- Apply skills to realistic problems.
- Commit meaningful work to GitHub.

## Codex CLI — Implementation Assistant

- Execute explicitly requested implementation tasks.
- Handle repetitive coding and documentation work.
- Inspect repository context before editing.
- Run appropriate commands and tests.
- Stay within the requested scope.
- Report changes and failures accurately.
- Never commit or push unless explicitly instructed.

---

# Core Learning Philosophy

**20% Learn · 80% Build**

Avoid tutorial hell.

Learn only what is necessary for the current task, then apply it immediately.

---

# Learning Loop

**Understand → Observe → Predict → Learn → Code/Build → Run → Debug → Review → Rebuild → Apply**

### Understand
Understand the problem and desired outcome.

### Observe
Study a relevant example or existing behavior.

### Predict
Predict what the code or workflow should do before running it.

### Learn
Learn only the concept required for the current task.

### Code / Build
Write or build the important part yourself.

### Run
Execute the code or workflow.

### Debug
Investigate failures before asking for the answer.

### Review
Review the implementation and reasoning.

### Rebuild
Recreate the concept without blindly copying.

### Apply
Use the skill on a new practical problem.

---

# Mastery Standard

A topic is not mastered simply because the workflow works.

The student should be able to:

- Understand
- Build
- Debug
- Explain
- Apply

---

# 90-Day Roadmap

## Month 1 — Foundation + First Workflow

### Week 1 — n8n Core + Deployment

Focus:

- Triggers
- Nodes
- Inputs / Outputs
- Connections
- Data Mapping
- Expressions
- Webhooks
- HTTP Requests
- Workflow Execution
- Local vs hosted n8n
- n8n Cloud
- Self-hosting concepts
- Environment variables
- Credential / secret handling

Build progressively:

1. Manual Trigger → data
2. Webhook → response
3. Webhook → transformation → response
4. Webhook → HTTP Request → response

Deployment goal:

- Understand local vs hosted execution.
- Understand what 24/7 automation requires.
- Deploy one working workflow using an appropriate hosting option.

---

### Week 2 — OpenAI API + AI Lead Enrichment

Focus:

- API requests
- Authentication
- Prompt / instructions
- Structured JSON
- Schema thinking
- Function / tool calling
- Error handling

Build Portfolio Project 1:

**AI Lead Enrichment & Personalized Outreach**

Concept:

**Authorized lead data → n8n → AI analysis → personalized message → review/approval → email → logging**

Use authorized data sources and respect applicable platform terms and privacy requirements.

Deliverables:

- `workflow.json`
- README
- Architecture explanation
- Screenshots
- Loom demo
- Test data
- Setup instructions

---

### Week 3 — GoHighLevel + Loom Strike

Focus:

- Sub-accounts
- Contacts
- Custom fields
- Tags
- Pipelines
- Opportunities
- Workflows
- Forms
- Email / SMS actions
- Basic integrations

Build:

**CSV / Form → GHL Contact → Tag → Pipeline → Follow-up**

Prepare personalized demonstrations:

- Choose a target niche.
- Identify a real problem.
- Build a relevant demo.
- Record a 1–2 minute Loom.
- Explain the problem.
- Show the automation.
- Show the expected outcome.

Core principle:

**Show the steel. Don't just describe it.**

---

### Week 4 — Beta Pilot + Case Study

Primary goal:

**First Beta Pilot**

A beta can be:

- Free
- Discounted
- Limited-scope

Potential evidence:

- Feedback
- Testimonial
- Case study
- Performance measurements

Do not assume a paying client is guaranteed within the first 30 days.

### ROI Rule

Never present simulated or estimated results as actual client results.

Use:

- Target
- Estimated
- Simulated

Only call a result a measured outcome when actual evidence exists.

---

# Month 2 — Portfolio + Client Acquisition

## Week 5 — Portfolio Project 2

**Appointment Reminder Automation**

Form → n8n → CRM → SMS / WhatsApp → Logging

Deliver:

- Workflow
- Documentation
- Screenshots
- Loom demo
- Test evidence

---

## Week 6 — Portfolio Project 3

**Invoice / Receipt Automation**

Google Form → n8n → AI extraction → PDF → Email → CRM / Log

Deliver:

- Workflow
- Documentation
- Screenshots
- Loom demo
- Test evidence

---

## Week 7 — Acquisition Setup

Prepare:

- Upwork
- OnlineJobs PH
- Fiverr
- LinkedIn
- Notion portfolio
- Carrd
- Loom
- Proposal template
- Discovery questions

Portfolio communication:

**Problem → Automation → Outcome → Proof**

---

## Week 8 — Outreach

Track:

- Messages sent
- Replies
- Calls
- Qualified opportunities
- Proposals
- Wins
- Losses
- Rejection reasons

Prefer personalized outreach over generic spam.

Use Loom when a short demonstration communicates the solution better than text.

---

# Month 3 — Delivery + Retention

## Weeks 9–10 — Client Delivery

**Understand Problem → Confirm Scope → Build → Test → Document → Demo → Deliver → Support**

---

## Week 11 — Retention

Potential recurring services:

- Maintenance
- Monitoring
- Small workflow changes
- Reporting
- Support
- Retainer

Recurring services must correspond to actual ongoing client value.

---

## Week 12 — Systematize

Create reusable:

- Proposal template
- Discovery checklist
- Client onboarding
- Testing checklist
- Delivery checklist
- Handover document
- Support SOP
- Retainer process

---

# Daily Accountability

Every meaningful session should leave evidence.

1. Define objective.
2. Learn the required concept.
3. Build.
4. Run.
5. Debug.
6. Review.
7. Record progress.
8. Commit meaningful work.
9. Push to GitHub.

---

# GitHub Evidence

Use meaningful commits such as:

- `Add n8n webhook exercise`
- `Document n8n expressions`
- `Add lead enrichment workflow`
- `Add deployment notes`
- `Record beta pilot results`

Do not create fake progress commits.

---

# Progress Tracking

**Notion**
- Detailed tracker
- Planning
- Session notes
- Personal reflections

**GitHub**
- Code
- Workflow files
- Technical documentation
- Exercises
- Project evidence
- Commit history

**ChatGPT**
- Teaching
- Review
- Debugging
- Challenges
- Learning direction

**Codex**
- Approved implementation assistance

---

# AI Usage Rules

AI may:

- Explain
- Review
- Debug
- Suggest
- Automate repetitive work

For important learning exercises, the student should attempt the implementation first.

AI should not automatically replace the student's learning.

---

# Security

Never commit:

- API keys
- Passwords
- Access tokens
- Client credentials
- Private secrets

Use environment variables and secure credential storage.

---

# Scope Control

Current primary stack:

**n8n + OpenAI + GoHighLevel**

Supporting tools are introduced only when required by a project.

The following are outside the current bootcamp focus:

- React
- MERN
- Advanced Python
- Machine learning
- Fine-tuning
- Building LLMs
- Learning every automation platform

Python is a supporting automation skill, not the primary curriculum.

---

# Long-Term Direction

**Learn → Build → Demonstrate → Sell → Deliver → Retain → Systematize**