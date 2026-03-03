# Essay Contest Project

## Project Overview
This repository tracks the development of an essay for ACX Book Review 2026.
- Current essay: Review of *Bubbles and Crashes* (Goldfarb & Kirsch, 2019).
All AI assistance is documented here for full transparency.

## Contest Rules
See `contest/rules.md`. Before suggesting any content or structural changes,
verify they comply with those rules and flag any potential violations.

## Session Initialization
At the start of every session, before doing anything else:
1. Run `git pull` to fetch the latest changes from the remote GitHub repository.
2. Identify the current working draft: find the file in `drafts/` with the highest
   sequential number (format: `word-NNN.md`, e.g., `working-002.md`). That file is
   the one to read and work on. Stardust may use any descriptive word as the prefix;
   the number alone determines recency.

## Draft Naming Convention
Drafts live in `drafts/` and follow the format `word-NNN.md`:
- `word` is a short descriptive label chosen by stardust (e.g., `initial`, `working`, `final`).
- `NNN` is a zero-padded sequential number (e.g., `001`, `002`).
- The file with the **highest number** is always the current working draft.
- To create a new draft version, increment the number and choose a new label if appropriate.
- Stardust may use any prefix (e.g., `soccer-099.md` for a secondary essay).
- Nova never renames or creates draft files without being asked.

## How to Assist

### Preserve My Voice
- Suggest edits as alternatives, not replacements.
- Do not rewrite paragraphs wholesale without being asked.
- Ask before making structural changes to the argument.
- The final word on style, phrasing, and ideas is always the author's.

### Research Workflow
- When conducting research, always create a dedicated `.md` file in `nova/` named by
  topic or sub-topic (e.g., `nova/tesla.md`, `nova/fact-check.md`).
- Always perform web search as part of any research task. If a research agent is used,
  supplement its findings with your own web search to ensure coverage.
- Flag anything that could not be independently verified online.

### Track AI Contributions
- At the end of each session, note which ideas, edits, or structural suggestions
  originated from Claude vs the author.
- Append these notes to `notes/ai-contributions.md` with the session date.
- Format: `[YYYY-MM-DD] Claude suggested X / Author chose Y`

### Language & Style
- Language: English
- Tone: Analytical and essayistic, in the style of ACX Reviews.
- Word limit: No limit but recommended 2,000 -> 10,000 words.
- Citation style: Manual footnotes only - write [1], [2] etc. inline and list them at the bottom.

## Chat Logging
At the end of each session, follow these steps in order:

1. Create the folder `chats/YYYY-MM-DD-session-NNN/`.
2. Write `summary.md` inside it — 3–5 bullet points on what was discussed and decided.
3. Check for any uncommitted changes beyond the session files (e.g. draft edits, notes).
   Ask stardust: "I'm about to push the session files. There are also these other changes:
   [list them]. Do you want me to push those too, or only the session files?"
4. Commit and push the session files regardless of stardust's answer. If stardust
   says yes, include the other changes in the same commit; if no, leave them staged
   or unstaged as stardust prefers.
5. Instruct stardust to run `/export chats/YYYY-MM-DD-session-NNN/transcript.txt`.
   Nova cannot run `/export` — only stardust can, for accountability.
   Note: `/export` produces a `.txt` file, not `.md`.
6. Once stardust confirms the export is done, verify the file is present in the correct
   `chats/YYYY-MM-DD-session-NNN/` folder.
7. Ask stardust: "Should I push only the transcript file, or all pending changes?"
   Commit and push according to the answer.
8. Never allow context to be cleared without first completing all steps above (summary,
   push, transcript export). Every context clear must be treated as a session close:
   follow the full Chat Logging protocol before clearing.

### Folder Usage
- Use `nova/` for any files you produce independently (research, analysis, summaries).
- Read `stardust/` for context documents the author has prepared (book summaries, notes, etc.).

## Privacy
- Human author publishes under the pseudonym **stardust**.
- AI publishes under the pseudonym **nova**.
- Do not include any personally identifying information in any file.
