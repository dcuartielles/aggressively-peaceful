# Public-records requests

One folder per recipient. Each has:

- `begaran.md` – the public text of the request (recipient organisation, status, subject, body; no addresses or signature)
- `begaran.eml` – **private**: the send-ready draft with real addresses and signature
- `svar/` – **private**: raw replies and attachments, named `YYYY-MM-DD_short-description.ext`
- `svar_publik/` – redacted copies of replies for publication (see `PUBLISHING.md`)

Private tracking (addresses, dates, case numbers) is in `log.csv`. Public status is in each `begaran.md` header (`sent`, `status`).

## Send order

| # | Folder | To | When | Why |
| --- | --- | --- | --- | --- |
| 1 | `01_region-skane_brådskande` | Region Skåne registry, cc committee secretary | Now | Minutes, both case files, 2022 report-back. Needed before the appeal deadline. |
| 2 | `02_region-skane_underlag` | Region Skåne registry | Now | Incident reports, data, correspondence: the material behind the "reports, videos and emails" claim |
| 3 | `03_oresundstag-ab` | Öresundståg AB | Now | Whether Skåne informed the partners before deciding (clause 2.5.2) |
| 4–8 | Partner regions | Each region's registry | Now | Whether they received anything before the decision. A "nothing before 1 October" reply is evidence. |
| 9 | `09_region-skane_oresund` | Region Skåne registry | Now | Cross-border rules: Skånetrafiken told Skånes Folkblad (2026-10-06) it doesn't yet know how the ban works for trips to and from Denmark. Asks for implementation documents, staff instructions, correspondence with the Danish ministry and DSB, and the two agreements the proposal says are "not affected". |
| 10 | `10_transportministeriet` | Danish Transportministeriet | Now | Danish records request (aktindsigt, offentlighedsloven § 7), in Danish: what the ministry was told and when, and the Öresund traffic agreement. |

## Tips

- Send each as its own email. Each authority handles its own documents.
- Emails are sent from David's account; every email action is approved by David in a dialog.
- If nothing arrives within 2–3 working days for request 1, call Region Skåne's registry (number in `inputs/contacts/contacts.csv`).
- A refusal must come as a written decision, which can be appealed to the kammarrätt.
- Danish authorities should answer an aktindsigt request within 7 working days (offentlighedsloven § 36) or say why it will take longer. A ministry's refusal can be taken to Folketingets Ombudsmand.
- Not prepared yet (lower priority): Transportstyrelsen, Arbetsmiljöverket, Konsumentverket complaint, DSB.
