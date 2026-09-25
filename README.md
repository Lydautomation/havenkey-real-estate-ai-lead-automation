# HavenKey — Real Estate AI Lead Qualification & Follow-Up Workflow

An AI-powered real estate lead management workflow designed to help property sales teams capture enquiries, assess buying readiness, prioritize prospects, and automate appropriate follow-up.

The workflow combines AI-powered lead qualification with automated routing, internal notifications, consultation scheduling, and customer communication while keeping final sales decisions under human control.

## The Problem

Real estate businesses can receive many property enquiries from prospects at different stages of the buying journey.

Some prospects may be ready to purchase immediately, some may require additional follow-up, while others may still be exploring their options.

When every enquiry is reviewed manually, sales teams must spend time examining prospect information, determining buying readiness, prioritizing leads, recording details, and deciding what action should happen next.

Without a structured qualification process, high-intent prospects can be difficult to identify quickly among other enquiries.

## The Solution

HavenKey uses an automated workflow to capture property enquiries and analyze prospect information using AI.

The system evaluates the information provided by each prospect and recommends one of three lead categories:

- **HOT** — high buying readiness and requires timely sales attention
- **WARM** — shows interest but requires additional follow-up
- **COLD** — currently better suited for nurturing

The AI also provides reasoning for its recommendation so the sales team can understand why a prospect was placed in a particular category.

The recommended category determines the next automation path while the sales team retains control over the final qualification and sales decision.

## Core Capabilities

- Capture incoming property enquiries
- Record prospect information automatically
- Analyze buying readiness using AI
- Recommend HOT, WARM, or COLD lead classification
- Provide reasoning for the qualification recommendation
- Route prospects according to their recommended category
- Notify the sales team about leads requiring attention
- Support automated prospect follow-up
- Schedule property consultations for qualifying prospects
- Maintain organized lead records
- Keep final sales decisions under human control

## How It Works

A typical property enquiry follows this process:

1. A prospect submits a property enquiry.
2. The workflow captures the prospect's information.
3. The lead is automatically recorded in Google Sheets.
4. AI analyzes the enquiry and assesses buying readiness.
5. The system recommends a HOT, WARM, or COLD classification.
6. The AI provides reasoning for the recommendation.
7. The lead is routed through the appropriate follow-up path.
8. Leads requiring sales attention are surfaced to the team through Slack.
9. Qualifying prospects can proceed to property consultation scheduling.
10. Appropriate email communication is sent to the prospect.
11. The sales team retains control over the final decision and subsequent sales actions.

## Lead Qualification

The qualification process considers information provided by the prospect to assess their level of buying readiness.

Rather than treating every enquiry equally, the workflow helps organize prospects according to the level of attention they may require.

### HOT

Prospects showing strong buying readiness are prioritized for timely sales attention.

### WARM

Prospects showing meaningful interest but requiring additional engagement are routed for follow-up.

### COLD

Prospects who are not currently ready to proceed remain suitable for future nurturing.

The classifications are AI-generated recommendations and do not replace the sales team's final judgment.

## Consultation Scheduling

For qualifying prospects, the workflow can support automated property consultation scheduling.

This reduces the number of manual steps between identifying a high-intent prospect and arranging the next stage of the sales conversation.

Scheduling remains part of the wider lead-management process rather than replacing human interaction with the sales team.

## Human-in-the-Loop Design

HavenKey is designed to support real estate sales teams rather than replace human judgment.

AI assists with analyzing enquiry information, assessing buying readiness, explaining qualification recommendations, and routing prospects.

The sales team remains responsible for final qualification decisions, property discussions, negotiations, and other important sales decisions.

## Tech Stack

**Automation & Orchestration:** n8n  
**Lead Capture:** Online Enquiry Form  
**AI / LLM:** AI-powered lead analysis  
**Lead Records:** Google Sheets  
**Internal Notifications:** Slack  
**Consultation Scheduling:** Google Calendar  
**Customer Communication:** Gmail

## Privacy & Data Handling

Public demonstrations and documentation for this project use fictional or test prospect information only.

No private customer information, API keys, authentication tokens, credentials, webhook secrets, or other sensitive information are included in the public project documentation.

---

**Built by Lydia Ogbene Odey**  
AI Automation Specialist | Health Tech Automation | Sales & CRM Automation
