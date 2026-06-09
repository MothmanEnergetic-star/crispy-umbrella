# Data Flow — AI Revenue Agent

Data movement and integration points for the AI Revenue Agent.

---

## Source to Destination Flow

1. **Lead Source**
   - Web forms
   - CRM imports
   - CSV uploads
   - Third-party APIs

2. **Enrichment**
   - Leads flow into the enrichment layer.
   - External APIs supplement company and contact data.
   - Prospect profiles are normalized.

3. **Qualification**
   - Enriched leads are scored.
   - ICP and intent rules determine readiness.
   - Qualified leads are marked for outreach.

4. **Outreach**
   - Messages are generated and queued.
   - Sequences execute across channels.
   - Engagement events are recorded.

5. **Booking**
   - Qualified prospects receive calendar availability.
   - Bookings are confirmed.
   - Meeting details are linked to the lead.

6. **CRM Sync**
   - Lead status, activities, and meeting results sync to CRM.
   - Pipeline and opportunity data update.

---

## Data Objects

- `Lead` — raw prospect and contact data
- `Enriched Lead` — lead with firmographic and intent data
- `Qualified Lead` — lead meeting the scoring threshold
- `Sequence Event` — outreach step and status
- `Booking` — calendar appointment details
- `CRM Record` — synced contact or deal data
