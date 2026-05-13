# AI Calling Strategy for Ditto Insurance

## PM Internship Case Study

---

# Overview

This repository contains a Product Management case study focused on designing an AI-powered calling assistant for Ditto Insurance.

The project explores how conversational AI can help recover missed consultation calls, activate dormant leads, and improve operational efficiency without replacing human insurance advisors.

The proposed solution introduces an AI assistant named **Diya**, designed specifically for customer rescheduling and lead engagement workflows.

---

# Problem Statement

Ditto Insurance operates on an inbound advisory model where users voluntarily book insurance consultation calls with certified advisors.

Although users show high intent by booking appointments, a significant percentage fail to attend scheduled calls. These no-shows directly impact:
- advisor productivity
- consultation conversions
- revenue opportunities

The challenge was to design an AI-powered system that:
- recovers missed consultations
- improves attendance rates
- maintains customer trust
- remains compliant with Indian regulations

---

# Business Opportunity

The sales funnel analysis identified that approximately 28–35% of booked calls go unattended.

For every 100 booked consultations:
- around 15–19 high-intent users miss their calls
- recovering even 40% of these users could generate 6–8 additional consultations

This creates a strong opportunity for automation in:
- no-show recovery
- lead activation
- post-consult follow-ups

The actual advisory conversation remains fully human-led.

---

# Sales Funnel Analysis

| Stage | Description | Estimated Conversion |
|---|---|---|
| Awareness | SEO, referrals, Finshots newsletter | - |
| Lead Capture | User fills insurance form | 5–8% |
| Slot Booking | Consultation scheduling | 45–55% |
| Call Attendance | User attends consultation | 65–72% |
| Advisory Call | Human advisor interaction | ~80% |
| Follow-up | Proposal engagement | 35–45% |
| Application | Policy purchase process | 28–35% |

---

# AI Intervention Strategy

## Priority 1 — No-Show Recovery

AI calls users who missed their scheduled consultation.

### Objectives
- reschedule missed calls
- reduce advisor manual effort
- recover lost conversions

### Why AI Fits Here
- simple conversational flow
- low regulatory risk
- measurable outcomes
- limited conversational complexity

---

## Priority 2 — Lead Activation

AI engages users who filled forms but did not schedule appointments within 48 hours.

### Tasks
- confirm intent
- offer booking slots
- route users to human advisors

---

## Priority 3 — Post-Consult Re-engagement

AI follows up with users who became inactive after receiving insurance proposals.

This stage was considered future scope due to higher conversational complexity.

---

# Platform Research & Evaluation

Three AI calling platforms were evaluated:

| Platform | Key Strength |
|---|---|
| Plivo | India-compliant telephony infrastructure |
| Retell AI | Strong developer tooling |
| Sarvam AI | Native Indian language and Hinglish support |

---

# Recommended Stack

## Sarvam AI + Plivo Telephony

### Reasons for Selection

### Sarvam AI
- native Hindi and Hinglish support
- Indian voice optimization
- lower operational cost
- India-hosted infrastructure

### Plivo
- DLT-registered telephony
- TRAI-compliant infrastructure
- reliable voice APIs

This combination provides:
- compliance
- scalability
- lower latency
- reduced operational cost

---

# AI Assistant Design — “Diya”

## Role
Diya acts as an AI scheduling assistant.

She:
- reschedules consultations
- activates leads
- escalates complex questions to humans

She never:
- recommends insurance policies
- gives financial advice
- replaces advisors

---

# Personality Design

| Attribute | Description |
|---|---|
| Tone | Warm and conversational |
| Language | English, Hindi, Hinglish |
| Communication Style | Transparent and helpful |
| AI Disclosure | Clearly identifies as AI |

---

# Sample No-Show Recovery Flow

### Opening

> “Hi, am I speaking with [First Name]?”

### Introduction

> “This is Diya, an AI assistant from Ditto Insurance. You had a consultation scheduled earlier today and we missed connecting.”

### Rescheduling Prompt

> “Would you like to reschedule your consultation?”

### Confirmation

> “You’ll receive a WhatsApp confirmation shortly.”

---

# Edge Case Handling

## Customer Scenarios

| Scenario | Handling |
|---|---|
| Customer busy | Retry later |
| Already connected | Suppress future AI calls |
| Not interested | Immediate opt-out |
| Policy question asked | Escalate to advisor |
| Customer angry | Respectfully disengage |
| Asked if AI | Transparently confirm |

---

# Technical Failure Handling

| Failure | Response |
|---|---|
| Call drops | Trigger WhatsApp follow-up |
| STT failure | Switch to WhatsApp |
| Platform outage | Pause campaign |
| No answer | Leave voicemail |

---

# Compliance Considerations

The system was designed considering:
- TRAI calling regulations
- DLT registration requirements
- IRDAI insurance compliance
- DND number suppression
- consent-based communication
- call recording retention policies

---

# Execution Roadmap

## Phase 0 — Foundations
- DLT registration
- vendor onboarding
- CRM preparation
- compliance validation

## Phase 1 — Script Design
- advisor interviews
- Hinglish conversational design
- fallback logic creation

## Phase 2 — Integration
- CRM webhook integration
- dashboard setup
- recording storage system

## Phase 3 — Pilot Launch
- 200 no-show lead pilot
- A/B testing
- transcript reviews

## Phase 4 — Expansion
- analyze KPIs
- improve scripts
- expand to additional workflows

---

# Data Design

## CRM Input Fields
- lead ID
- customer name
- phone number
- insurance interest
- language preference
- scheduled slot
- DNC status

## AI Output Fields
- call outcome
- call duration
- sentiment score
- rescheduled slot
- escalation flags
- transcript links

---

# KPI Framework

| KPI | Target |
|---|---|
| No-show recovery rate | >30% |
| Contact rate | >55% |
| Opt-out rate | <5% |
| Attendance after reschedule | >70% |
| Human escalation rate | <10% |

---

# Operations Dashboard Design

The proposed dashboard tracks:
- total calls made
- contact rates
- opt-outs
- rescheduled consultations
- escalation queues
- sentiment trends
- funnel performance

---

# Calling Window Strategy

| Time Window | Priority |
|---|---|
| 11 AM – 1 PM | High |
| 5 PM – 8 PM | High |
| 9 AM – 11 AM | Medium |
| Before 9 AM / After 9 PM | Blocked |

This strategy aligns with TRAI regulations and customer availability patterns.

---

# Key Learnings

This case study demonstrates:
- product thinking
- AI workflow design
- customer journey analysis
- operational strategy
- compliance-aware automation
- KPI-driven experimentation

---

# Repository Contents

| File | Description |
|---|---|
| `SAI TEJA_CASE STUDY_SKILLO VILLA.pdf` | Full PM case study document |

---

# Skills Demonstrated

- Product Management
- AI Workflow Design
- CRM Strategy
- Conversational AI
- Operations Planning
- KPI Definition
- Business Analysis
- Compliance Research
- User Flow Design

---

# Future Improvements

Potential future enhancements:
- multilingual regional support
- AI sentiment detection
- WhatsApp conversational workflows
- advisor performance analytics
- predictive no-show scoring

---

# Sources & Research References

Research references used in this case study include:
- Ditto Insurance public resources
- TRAI regulations
- IRDAI compliance guidelines
- Sarvam AI documentation
- Plivo pricing and APIs
- industry conversion benchmark reports

---

# Connect

If you found this project interesting, feel free to connect and discuss Product Management, AI workflows, and business strategy.

## Author
Sai Teja
