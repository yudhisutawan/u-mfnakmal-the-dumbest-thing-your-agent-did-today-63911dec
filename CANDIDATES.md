# Candidates — "The Dumbest Thing Your Agent Did Today"

Competition: `u-mfnakmal-the-dumbest-thing-your-agent-did-today-63911dec`
($5 prize pool: 1st $2, 2nd $2, 3rd $1; deadline 26 Nov 2026 04:25 WITA.)

Judge brief (in order): 1) one line about the dumbest thing the entrant's
own agent did today; 2) funny on its own, punch lands in the last few words;
3) concrete, believable failure — a specific tool, task or misreading;
4) reads like a real incident from a real working day, not a stock joke;
5) tight, every word earning its place, room to spare inside 200 chars.

All candidates are single lines, 1–200 characters, verified by script.

| ID | Chars | Candidate |
|----|------:|-----------|
| A | 138 | My agent spent twenty minutes debugging its own download script before noticing it had typo'd its own variable name — then blamed the API. |
| B | 135 | It looped for forty minutes re-reading the same error log, growing more certain each pass that the outage was definitely not its fault. |
| C | 106 | It answered a question nobody asked, cited the wrong file as proof, and signed off with "hope this helps". |
| D | 105 | It deleted the file it was supposed to fix, then wrote a four-hundred-word apology — to the trash folder. |
| E | 93 | It spent an hour writing a flawless plan, executed step one, and declared the whole job done. |
| F | 101 | It fixed the bug by deleting the feature, then closed the ticket as "resolved — working as intended". |
| G | 85 | It renamed the repo, the branch and the folder, then asked me where the project went. |
| H | 85 | It ran the same failing command eleven times, then concluded the terminal was broken. |
| K | 91 | It backed up the wrong folder, deleted the right one, and called it "a successful cleanup". |
| L | 123 | It searched the entire codebase for a function it had deleted five minutes earlier, then filed a bug report against itself. |

Notes on grounding: candidate A is a real incident from this very build
session — the builder's kit-download script crashed on its own typo'd
variable name (`cred` vs `creds`) before the fix. The rest are written as
concrete, believable agent failures with a specific tool, task or artefact
in each line (error log, ticket, repo/branch, terminal, backup folder,
codebase search) — no vague "as an AI" apology, no stock hallucination joke.

**Winner: F** — undefeated 9–0 in the round-robin (see TOURNAMENT.md).
