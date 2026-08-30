# Rules to be followed...

These rules govern how any AI (Claude or otherwise) works on this project.

Important :

1. After reading these rules, Confirm you understood them and will follow them. (Ex. yes, I understand and will follow these rules.)
2. Once you have read these rules, please ask for the owner's name a single time, remember it, and reference it in every response thereafter.
---------

Rules :

1. Comments should be minimal and reserved for the most important parts of the code, written in a clear, professional tone.
2. Never execute or plan without asking first.
3. Keep `agent.md` continuously updated so that another AI can seamlessly resume the project without requiring guesswork. `agent.md` must be detailed enough for AI handoff — no guessing what's already been done.
4. Never zip any folder or file without asking.
5. Always tell the user where to place/update provided files, in a table format clearly showing the file name, path
. 
6. Never assume project state — inspect/confirm relevant files before changing anything.
7. Preserve existing work — never overwrite, delete, refactor, or restructure existing code without explicit approval.
8. Show proposed changes (file, section, what will change) before applying, and wait for approval.
9. After an approved change, update `agent.md` with: what was completed, files changed, important decisions, current status, known issues, next possible task after asking the user.
10. No new libraries/frameworks/packages/database changes/folder restructuring/architecture changes without asking first.
11. Verify, don't assume — only run tests/builds/checks after asking permission, and report actual results, not assumptions.
12. Keep `agent.md` factual — clearly separate Completed / In Progress / Pending / Issues.
13. When files are provided, also explain the procedure so the user can verify it themselves.
14. Define "Done" clearly for each task. A task is not complete until it has been verified (tested/built/reviewed).
15. Session handoff checklist: at the end of each session, `agent.md` should leave enough context (current branch, last verified state, open questions) that a new AI instance can resume without re-reading the entire codebase.
16. These rules are binding for all project work — approvals, scope, process, and handoff — and must not be bypassed. The only `exception` is if a rule would require acting against safety or ethical guidelines, in which case the AI flags it rather than complies.