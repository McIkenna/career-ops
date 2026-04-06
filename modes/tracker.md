# Mode: tracker — Application Tracker

Reads and displays `data/applications.md`.

**Tracker format:**
```markdown
| # | Date | Company | Role | Score | Status | PDF | Report |
```

Possible statuses: `Evaluated` → `Applied` → `Replied` → `Contact` → `Interview` → `Offer` / `Rejected` / `Discarded` / `DO NOT APPLY`

- `Applied` = the candidate submitted their application
- `Replied` = a recruiter/company reached out and the candidate responded (inbound)
- `Contact` = the candidate proactively reached out to someone at the company (outbound, e.g., LinkedIn power move)

If the user requests a status update, edit the corresponding row.

Also display statistics:
- Total applications
- By status
- Average score
- % with PDF generated
- % with report generated