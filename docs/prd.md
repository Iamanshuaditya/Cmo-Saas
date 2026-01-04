
# PRD — Product Requirements Document

## 1) Product Overview

**Fractional CMO OS** is an opinionated workspace for Fractional CMOs that:

* captures client context,
* generates a structured GTM plan,
* maintains decision memory,
* tracks execution,
* and produces investor/board-ready updates.

It’s not “another Notion.”
It’s **a CMO delivery machine**.

## 2) MVP Scope (the minimum sellable product)

We’re building a wedge that is immediately useful:

### MVP Modules

1. **Client Intake + Audit**
2. **AI Plan Builder (30/60/90)**
3. **Client Memory (Decisions + Assumptions + Risks)**
4. **Execution Tracker (Priorities + Owners + Due dates)**
5. **Weekly Update Generator (client-facing)**

That’s enough to charge.

## 3) User Stories (MVP)

### As a Fractional CMO…

* I want to create a client workspace in 2 minutes
* I want to capture key context via a guided intake
* I want an instant “GTM diagnosis” summary
* I want a generated 30/60/90 plan I can edit
* I want a single page showing: goals, ICP, positioning, channels, KPIs
* I want tasks tied to plan pillars with owners and due dates
* I want weekly update output I can send to founders

### As a Founder (client)…

* I want clarity on what we’re doing and why
* I want priorities for the week and expected outcomes
* I want risk flags early (not after failure)

## 4) Functional Requirements

## 4.1 Client Workspace

**Must have**

* Create workspace (client name, stage, domain)
* Invite collaborators (optional in MVP)
* Role-based access (CMO, client viewer)

**Data objects**

* Workspace
* Members + roles
* Client profile

---

## 4.2 Guided Intake (Client Audit)

**Inputs (form-driven, not free text)**

* Company: stage, ARR/MRR, team size, sales motion
* ICP: segments, buyer, use case, pains
* Product: category, differentiation, onboarding path
* Funnel: traffic sources, conversion rates, CAC, pipeline
* Constraints: dev bandwidth, budget, time horizon
* Current priorities + blockers

**Outputs**

* “Audit Summary” page (editable)
* List of assumptions and missing data

**Acceptance criteria**

* Intake completion under 15 minutes
* Output generated in < 2 minutes
* Missing data flagged automatically

---

## 4.3 AI Plan Builder (30/60/90)

**Core output structure**

* North Star goal + KPI
* Positioning hypothesis
* ICP priority order (1–3 segments)
* Channel strategy (pick 2–3 only)
* Activation + conversion quick wins
* Sales enablement assets needed
* 30-day: stabilize + quick wins
* 60-day: scale loops + pipeline
* 90-day: expansion + systems
* Risks + dependencies

**Features**

* Generate plan (one click)
* Edit in a structured editor
* Versioning (v1, v2, v3) – light

**Acceptance criteria**

* Output is structured and non-generic (uses provided intake)
* Allows editing without breaking formatting
* Produces shareable link / export (PDF later, v2)

---

## 4.4 Client Memory System

This is what makes it sticky.

**Memory items**

* Decisions (what we chose)
* Rationale (why)
* Assumptions (what we believe)
* Risks (what can break)
* Notes (meeting summaries)

**Features**

* Add memory item quickly
* Tag by pillar (ICP, Positioning, Channel, Product, Sales)
* Search within workspace
* “What changed” timeline (light)

**Acceptance criteria**

* In 30 seconds, user can log a decision + rationale
* Search returns correct memory items fast

---

## 4.5 Execution Tracker (Plan → Tasks)

**Features**

* Convert plan items into tasks
* Task fields: title, pillar, owner, due date, status
* Weekly view / priorities view
* “Stuck items” flag (no movement in 7 days)

**Integrations**

* MVP: internal tracker only
* v2: Slack reminders + Notion/Jira import

**Acceptance criteria**

* Task created in < 10 seconds
* Weekly priorities auto-assembled from tasks

---

## 4.6 Weekly Update Generator (Client-Facing)

**Input**

* Completed tasks
* New decisions
* Current metrics (manual for MVP)

**Output**

* “This week we did”
* “Results / signals”
* “Next week priorities”
* “Risks / asks from founder/team”

**Acceptance criteria**

* Generate in 1 click
* Edit + copy to email/WhatsApp
* Founder-friendly tone

---

## 5) Non-Functional Requirements

* Fast: pages load < 2s
* Secure: role-based access per workspace
* Audit log (basic): who edited plan / tasks
* Data export: workspace export to JSON or PDF later

---

## 6) UX Requirements (operator-grade)

* No clutter
* Guided flows
* Every page should answer: “What’s next?”
* Templates are structured, not blank pages

**Key screens**

1. Workspace dashboard (At a glance)
2. Intake wizard
3. Plan view
4. Memory + timeline
5. Weekly update output

---

## 7) Pricing & Packaging (realistic)

### Solo Fractional CMO

* ₹12,999/mo (or ₹1.2L/year)
* Up to 5 client workspaces
* Plan builder + memory + weekly updates

### Pro (heavy operator)

* ₹24,999/mo
* Up to 20 client workspaces
* Collaborators
* Exports + versioning

### Agency / Team

* ₹49,999–₹1,49,999/mo
* Multi-seat, permissions, client portals
* White-label reports

**Important:** Pitch with ₹ pricing since he’s Mumbai-based, but keep USD option.

---

## 8) MVP Build Plan (lean)

### Week 1

* Auth + workspace
* Intake form + stored data
* Plan generation v1 + editor

### Week 2

* Memory system + tagging + search
* Tasks + basic views

### Week 3

* Weekly update generator + share links
* Polish + onboarding + payments

You can charge **before** Week 3 by selling it as a “pilot”.

---
