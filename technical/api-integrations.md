# API Integrations — AI Revenue Agent

External services and integration details.

---

## Required APIs

### Clearbit
- Purpose: company and contact enrichment.
- Data: firmographics, technology stack, company size.

### Apollo
- Purpose: contact discovery and firmographic enrichment.
- Data: email addresses, job titles, company details.

### LinkedIn
- Purpose: profile discovery and outreach insights.
- Data: public profile URLs, titles, company names.

### Calendly
- Purpose: calendar availability and meeting booking.
- Data: available time slots, event creation, confirmation.

### HubSpot / GoHighLevel
- Purpose: CRM sync for contact/opportunity updates.
- Data: lead fields, stage updates, activity logs.

### Email Provider
- Purpose: sending outreach emails.
- Data: email content, send status, open/click events.

### OpenAI (or LLM provider)
- Purpose: outreach copy generation and objection handling.
- Data: prompts, generated message content.

---

## Integration Notes
- Store keys securely in a vault.
- Use retry and backoff for external calls.
- Log errors and webhook events for debugging.
