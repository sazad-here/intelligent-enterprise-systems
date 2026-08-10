# Evidence — SAP System Screenshots

Screenshots showing hands-on work in SAP S/4HANA 2022 (Fiori 3.0).

> **Nothing is committed to this folder until it has been redacted.**
> `.gitignore` blocks image files here by default. Remove that rule only after
> working through the checklist below.

---

## Redaction checklist — apply to every image before committing

The original screenshots are full-screen captures taken to satisfy a coursework
requirement (they had to show browser tabs and the taskbar to prove authorship).
That makes them unsuitable for publication as-is. Every one of the following
must be removed:

| # | What to remove | Why |
|---|---|---|
| 1 | **Personal email address and account name** in the browser profile and Outlook tab | Personal contact details |
| 2 | **The Outlook / Mail tab** entirely | Shows a private inbox |
| 3 | **WhatsApp and GroupMe tabs** | Private messaging; one tab title contains another student's full name |
| 4 | **All other browser tab titles and bookmarks** | Unrelated personal browsing |
| 5 | **The SAP server hostname and port in the URL bar** | Hosting institution's internal infrastructure; do not publish |
| 6 | **The Blackboard / "View Assessment" tab** | Identifies the graded assessment |
| 7 | **The Windows taskbar** | Weather widget, notification counts, open applications |
| 8 | **The user initials avatar** in the SAP shell header | Identifies the account |

**What to keep:** the SAP application area itself — the report, the transaction
screen, the data. That is the only part with any evidentiary value.

**Easiest method:** crop to the SAP content area only. That removes items 1–4 and
6–7 in a single action. Then blur or block out the URL bar (5) and the avatar (8)
if they fall inside the crop.

---

## Recommended set — six screenshots

Chosen because each shows substantive analytical work rather than a data-entry
screen. Source files are in the coursework folder, not in this repository.

| Target filename | Source | Shows |
|---|---|---|
| `01-project-cost-report.png` | `14.PNG` | Project P/2672 Act/Commitment/Total/Plan cost report by cost element — the actual-vs-commitment distinction described in [project accounting](../03-process-documentation/project-accounting.md) |
| `02-cost-center-planning.png` | `Exam 1/14C.PNG` | Cost centre planning report showing assessment, activity allocation, and under/over-absorbed overhead |
| `03-project-network-graph.png` | `Ans 3.PNG` | Network activity graph with early/late dates and float — the critical path |
| `04-project-builder-wbs.png` | `Ans1.PNG` | WBS hierarchy and network activity structure |
| `05-secondary-cost-element.png` | `Exam 1/3(3).PNG` | G/L account master for a secondary cost element |
| `06-network-confirmation.png` | `QUERY.PNG` | Activity confirmation with planned vs actual vs forecast duration |

Six is deliberate. A recruiter will open one or two; a folder of forty signals
inability to prioritise.

---

## What is deliberately not published

The completed case-study answer templates are excluded from this repository.
They are graded submissions for a course that is still running, and publishing
worked solutions would be an academic integrity problem regardless of who
benefits.

The SAP UCC Magdeburg curriculum PDF is excluded because it is copyrighted
teaching material and not mine to redistribute.

Peer evaluations of named teammates are excluded because they are other people's
performance data.

The analysis, process documentation, and findings in this repository are my own
work and are published deliberately.
