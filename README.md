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
| `drafts/` | Versioned essay drafts, named `word-NNN.md` (e.g., `initial-001.md`, `working-002.md`). The highest number is always the current working draft. |
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

## Why publish this?
Full transparency about AI assistance: every suggestion, revision, and
conversation is committed here so readers and contest organisers can judge
the extent and nature of AI involvement for themselves.
