# Publishing rules – aggressively peaceful

This folder is the working copy of the repository **aggressively peaceful**: a transparent record of how we are looking into Region Skåne's 2026 ban on bikes on trains. The repository is published as a website on GitHub Pages.

## What is published

- Indexes of press coverage, legal references and political decisions, **with links to the originals**
- Our own text: analysis, timeline, transcriptions and summaries
- The request templates we send (`outputs/requests/*/begaran.md`), without addresses or signature
- Redacted replies (`outputs/requests/*/svar_publik/`)

## What is never published

Enforced by `.gitignore`:

| Kept out | Why |
| --- | --- |
| `inputs/contacts/` | Names, emails and phone numbers |
| `inputs/notes/` | Research notes: may contain names and unverified claims |
| `outputs/requests/log.csv` | Email addresses and tracking details |
| `*.eml` | Send-ready drafts with real addresses and our signature |
| `outputs/requests/*/svar/` | Raw replies, which show the names of the people who answered |
| `*.pdf`, Office files, images | Original documents: we link to them instead |

## Redacting replies

Raw replies go in `svar/` (private). For each reply, write a public copy in `svar_publik/YYYY-MM-DD_short-description.md`:

- Remove names, email addresses, phone numbers, titles that identify a person, and signatures. Write `[handläggare]`, `[registrator]` etc.
- Keep the organisation, dates, case numbers (diarienummer) and the substance of the reply.
- List attached documents by title and date; link to them if the authority has published them. Do not upload them.
- If a document is refused, publish the refusal decision text (redacted) and the legal ground cited.

## Email

- Requests are sent from David's personal account.
- **Every interaction with the email account needs David's explicit approval in a dialog**: creating a draft, sending, searching or reading the inbox, labelling. Nothing happens in the background.
- Checks for replies are therefore run on request, or as reminders that ask for approval before looking.

## Before each commit

1. `git status`: check nothing from the list above is staged.
2. Search the files you are adding for `@` and phone numbers.
3. Check that only elected politicians are named; everyone else is described by role (names policy in `README.md`).
