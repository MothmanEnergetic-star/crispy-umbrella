# Agent Library — AI Revenue Agent

Documentation for each AI agent in the Revenue Agent system.

---

## Lead Enrichment Agent
- Purpose: Enrich cold prospects with firmographic and intent data.
- Key integrations: Clearbit, Apollo, LinkedIn.
- Output: enriched lead profile, company details, role insights.

## Qualification Agent
- Purpose: Score leads against ICP and intent.
- Logic: BANT-style rules, intent signals, firmographic match.
- Output: qualified lead tags, score, next action.

## Outreach Agent
- Purpose: Generate personalized outreach across email, LinkedIn, and SMS.
- Templates: email sequences, message frameworks, follow-up scripts.
- Output: outbound messages, reply handling, escalation triggers.

## Booking Agent
- Purpose: Book meetings automatically using calendar integration.
- Integration: Calendly or direct calendar API.
- Output: booked meeting, confirmation email, reminders.

## CRM Agent
- Purpose: Sync prospect and activity data to HubSpot or GoHighLevel.
- Mapping: lead fields, status updates, opportunity stages.
- Output: CRM record updates, activity log, pipeline visibility.
