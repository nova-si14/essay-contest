# Essay Contest — Transparent AI-Assisted Drafting

## What is this
I (the author) have created this repo in order to be able to publicly document AI involvement in essay contest submissions.

- **Human author pseudonym:** stardust
- **AI pseudonym:** nova

My (human) contributions will be done exclusively through the "stardust" account, mostly through GitHub web.
The AI (Claude) contributions will be done exclusively through the "nova" account, mostly through a terminal authenticated via the GitHub CLI.
Thus, commit history directly reflects who contributed what.

## Structure
| Path | Contents |
|------|----------|
| `contest/rules.md` | Contest rules as provided |
| `drafts/` | Every draft revision, versioned by date |
| `chats/` | Full transcripts and summaries of all Claude sessions |
| `notes/ai-contributions.md` | Running log of AI vs author contributions |
| `CLAUDE.md` | Instructions given to Claude at the start of each session |
| `stardust/` | Human-written docs for AI context (e.g. book summary, reading notes) |
| `nova/` | AI-written outputs for human use (e.g. research, analysis) |

## How it works
For this purpose, I (stardust) created the "nova" GitHub account beforehand, and set up the authenticated GitHub CLI on the same device where Claude Code is installed.

For additional transparency, I've instructed the AI to:
- Log our chat sessions in the folder `chats/`.
- Annotate the contributions in the file `notes/ai-contributions.md`
- Utilize the folder called `nova/` for any files that it produces on its own.

From my own part, I will also use the folder called `stardust/` for the inputs that I want the AI to read.

## How a session works

Each contest lives on its own branch (e.g. `dwarkesh-ai-2026`). `main` stays a clean template; per-contest content — filled-in `CLAUDE.md`, pasted `contest/rules.md`, drafts, chats, notes — accumulates on the branch.

**Session start (nova).** Read `CLAUDE.md`, the latest file in `drafts/`, and `notes/ai-contributions.md`. State what was read before producing any output.

**During the session.**
- nova proposes alternatives, not replacements (see `CLAUDE.md` → Preserve My Voice).
- nova asks before structural changes to the argument.
- Factual claims come with a primary source or an explicit flag of uncertainty (see `CLAUDE.md` → Substance & Honesty).

**Session end (nova).**
1. Save the session under `chats/YYYY-MM-DD-NNN/` as `transcript.md` and `summary.md` (see `CLAUDE.md` → Chat Logging).
2. Append a dated entry to `notes/ai-contributions.md`.
3. Commit on the contest branch and push.

**Merging back to main.** When a contest is complete, stardust merges the branch via GitHub web. The merge commit reflects the human's authorship of the decision to publish.

## Why publish this?
Full transparency about AI assistance: every suggestion, revision, and
conversation is committed here so readers and contest organisers can judge
the extent and nature of AI involvement for themselves.
