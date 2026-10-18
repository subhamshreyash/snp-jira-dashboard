# SNP Jira Dashboard

Template for the "SNP Ticket Desk" live dashboard artifact.
`dashboard_template.html` contains two placeholder tokens:
- `__DATA__` — replaced with a minified JSON array of SNP tickets assigned to the user
- `__PULLED__` — replaced with the pull timestamp (ISO, +05:30)

Refreshed daily by a Claude cloud routine that re-queries Jira and republishes the artifact.
