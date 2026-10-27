# donor-reports

Static copies of DPVA's donor-score reports, served at https://donors.vadems.org
(behind a Cloudflare Access login).

- `playbook.html`: Donor Score Fundraising Playbook
- `breakdown.html`: Donor Score Breakdown dashboard

The source lives in `C:\repos\finance\donor-pipeline\reports\donor-scores\`
(see that folder's `reports\README.md`). These files are copies; update the source first,
then re-copy here. `playbook.html` is the source fragment wrapped in a doctype/head with
a noindex tag. `breakdown.html` gets a noindex tag and a shorter snapshot line.

Aggregate counts only, no names or voter IDs.
