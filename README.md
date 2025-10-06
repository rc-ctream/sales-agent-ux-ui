# RAMI Dashboard – UX/UI Design Task

## 🚀 Introduction

The **RAMI Dashboard** is a **control and monitoring interface** for AI-powered **Sales Agents**.
Each agent acts as a digital salesperson capable of performing predefined **sales workflows** — from lead qualification to outreach and reporting.

Administrators can:

* **Create** new AI Sales Agents,
* **Build and configure workflows** for each agent using predefined tasks, and
* **Monitor** all agent activities in real time via a central activity log.

The dashboard aims to combine **usability**, **visual clarity**, and **intelligent automation** — showing not just static task lists, but **interactive workflows** that illustrate how each AI Sales Agent operates.

The integrated **Activity Log** displays in detail which agent is working on which part of their workflow and what the current task status is (*in progress*, *completed*, *failed*).

---

## 📖 User Story

**As a Company Administrator**
I want to create and manage **AI Sales Agents** in the **RAMI Dashboard**,
assign and organize their predefined tasks into **visual workflows via drag & drop**,
and monitor their activity log and current task statuses,
so that I can clearly see how each agent performs across their entire sales process.

---

## ✅ Acceptance Criteria

### 1. Create Sales Agents

* I can define the agent’s **name, description, avatar/icon, and sales focus** (e.g., inbound, outbound, CRM).
* The agent is saved in my **overview list** and becomes immediately visible.

### 2. Build Workflows (Task Assignment via Drag & Drop)

* I can drag predefined tasks from a **task library** onto a **workflow canvas** to create a custom process for each Sales Agent.
* Tasks are visually connected (e.g., arrows or nodes) to represent the sequence of actions.
* I can **reorder, remove, or connect** tasks to modify the workflow.
* Each workflow can be **saved, previewed, or activated/deactivated**.

### 3. Dashboard Overview & Activity Log

* I can see all agents with their **status** (*active, paused, offline*).
* I can view each agent’s **workflow diagram** and track which task is currently being executed.
* The **Activity Log** lists all actions with timestamps and task status (*in progress, completed, failed*).
* *(Optional)* I can filter logs by **date range**, **workflow name**, or **status**.

---

## 🎨 Design Task (for Candidate)

👉 Please design **4–5 key screens** as wireframes or mockups:

1. **Sales Agent Dashboard** – overview of all agents (list or card view with status indicators).
2. **Agent Creation Form** – input form for defining agent details and sales focus.
3. **Workflow Builder** – drag & drop interface for arranging predefined tasks into a visual workflow.
4. **Agent Workflow View** – diagram or flow representation showing the current state of the agent’s active workflow.
5. **Agent Activity Log** – timeline or table displaying all executed tasks and their status.

*Deliverables:*

* Wireframes or mockups (low- or high-fidelity)
* Formats accepted: Figma, Sketch, Adobe XD, or PNG/PDF exports

---

## 📋 Predefined Task Library for Sales Agents

These predefined tasks can be used as **building blocks** in the workflow builder.
Each task can be dragged onto the workflow canvas and visually connected to others.

### 🔹 Lead & Prospecting

* **Lead Qualification** – score and validate incoming leads.
* **CRM Data Entry** – update and maintain lead/customer records.
* **Social Media Lead Capture** – extract leads from LinkedIn, Facebook, or other platforms.

### 🔹 Communication & Outreach

* **Email Outreach** – send first-contact messages or follow-ups automatically.
* **FAQ Responses** – reply to frequent product or service questions.
* **Follow-up Reminders** – schedule automatic reminders for next contact steps.
* **Call Scheduling** – arrange phone or video meetings with prospects.
* **Demo Coordination** – plan and confirm demo appointments.

### 🔹 Deal Management

* **Proposal Drafting** – create initial sales quotes or offer templates.
* **Deal Prioritization** – rank opportunities based on conversion probability.
* **Pipeline Monitoring** – identify stagnating or inactive deals.
* **Competitor Mention Tracking** – flag competitor mentions during interactions.
* **Upsell/Cross-sell Suggestions** – recommend additional or related products.

### 🔹 Reporting & Insights

* **Sales Report Generation** – generate weekly/monthly summaries of sales performance.
* **Task Escalation** – forward complex or blocked tasks to a human manager.

---

## 🛠️ Notes for the Candidate

* The **Workflow Builder** should support **drag & drop** with clear visual feedback (connecting lines, node highlights, task icons).
* Each task should have a **short description or tooltip**.
* The **Agent Dashboard** should allow switching between list view and workflow view.
* Use **consistent visual indicators** for agent and task statuses (e.g., green = active, yellow = pending, red = failed).
* Prioritize **clarity, modularity, and scalability** in your design.
