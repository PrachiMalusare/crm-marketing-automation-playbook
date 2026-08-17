# CRM Data Model and Lifecycle

## Minimum viable contact record

| Field | Purpose | Example |
|---|---|---|
| Full name | Identity | Riya Mehta |
| Business email | Communication and deduplication | riya@company.in |
| Company | Account association | Example Systems |
| Role / seniority | Buying influence | Operations Head |
| Industry | Segmentation | Manufacturing |
| Employee band | Company-fit signal | 51–200 |
| Location | Territory routing | Pune |
| Product interest | Relevance | CRM implementation |
| Lead source | Attribution | Organic search |
| Original campaign | First-touch context | CRM audit guide |
| Consent status | Communication control | Opted in |
| Lifecycle stage | Funnel position | MQL |
| Lead owner | Accountability | SDR West |
| Last meaningful activity | Recency | Demo request |

Use controlled dropdown values for reporting fields. Avoid free text where a standard taxonomy is possible.

## Lifecycle stages

| Stage | Entry rule | Exit rule |
|---|---|---|
| Subscriber | Opted into educational updates | Provides identifiable business interest |
| Lead | Known contact with a relevant interaction | Meets fit and engagement threshold |
| MQL | Marketing-qualified by score and exclusions | Accepted or rejected by sales |
| SQL | Sales confirms need and relevance | Discovery completed |
| Opportunity | Defined need, stakeholder, and next step | Won, lost, or disqualified |
| Customer | Commercial agreement completed | Renewal/churn process |
| Evangelist | Customer willing to advocate | Status reviewed periodically |

## Governance rules

- Deduplicate primarily by normalized business email; review shared inboxes manually.
- Preserve original source while updating latest source separately.
- Require a reason when an MQL or opportunity is rejected/disqualified.
- Restrict sensitive fields through role-based permissions.
- Set retention and deletion policies with the organization’s legal/privacy owner.
- Run a monthly audit for missing owners, invalid emails, stale stages, and duplicates.

