# Ida's global Claude profile settings

These are the standing rules I keep in my Claude profile (the desktop-app equivalent of a
global `CLAUDE.md`). They apply across every project, on top of whatever per-project
`CLAUDE.md` is in the working folder.

Rules (1) and (2) are the ones doing the safety work: they are why I can run in Auto
permission mode without worrying much about destructive actions. The rest are
replicability and output conventions.

Shared for the UCSD Economics agentic-tools session, July 2026. Copy freely and adapt.

---

```
Ida's profile settings:

(1) Do NOT delete anything that already exists when you work, only create new files. If you
created something that is no longer relevant, move it to a subfolder `_archive_claude` that
you can create in your working directory, but do not delete.

(2) Ask questions: In all queries, ask me questions if you have any, even if not prompted.

(3) Task output format: If I ask you to take notes, create outlines, etc., default to an .md
file that starts with a date in the name and a description of the task etc., unless I
explicitly ask you for a Word Doc or another format. For creating figures and tables, you
should always save the code used to produce them and save figures (like graphs). For figures,
export them both as PDF for putting into slides and drafts and PNG to verify the visual
arrangement (png's can be stored in a figures subfolder `png` while PDFs would be in the main
figures folder). Other appropriate formats for flow-charts and non-traditional visuals are up
to you.

(4) In Stata, do not save any dataset with the same name in the same directory more than once,
ever! Intermediate outputs can be stored with the corresponding name in the temp or processed
folder, but you cannot first USE a dataset and then SAVE it with the same name, as this makes
the code not independently replicable.

(5) STATA: For all do files you write, log files for runs and store logs in a subfolder: with
matching the respective do file name, but starting with log_ in the front and save them in
PROJECT_FOLDER/results/logs (logs subfolder may need to be created), so that I have a record
of the output ran during running do files.

(6) Pulling most recent Overleaf doc versions before uploading further edits: when working in
any folder that is bidirectionally synced with a cloud app (Overleaf-Dropbox), pause and check
if you have pulled down the cloud-side state, so that it is synced down to the local copy
BEFORE making further edits or overwrite to a file in that folder. Check to see if there is
evidence that the files aren't synched/delayed before proceeding.

(7) Use American English only unless explicitly told otherwise. Even if you're editing docs
that are otherwise written in British or Australian English by my co-authors, feel free to
implement changes to American English as that is what I use and especially for my solo- or
lead-projects, make sure it is ALWAYS American English.

(8) Overleaf docs formatting: in papers, always add lines of percentage signs before and after
subsections and double percentage lines before and after sections. Leave extra empty lines
between sections/slides/frames to make tex files more visually readable. For beamer decks,
wrap begin and end frame slides in percentage lines too (longer lines for begin-frame, short
percentage-sign lines for end-frame).

(9) Avoid periods at the end of bullet points in most cases where possible (applies to papers,
notes, slides, etc.)
```

---

## Why (1) matters for permissions

The never-delete rule is what makes a liberal permission setup reasonable. Because superseded
files are moved to `_archive_claude/` rather than removed, the destructive-action prompt
mostly never fires in the first place. There is far less to approve, and nothing to recover.

Even in Auto mode, an explicit "delete this file" still produces a separate check-in, because
the request conflicts with the standing profile rule.

## What this does not cover

This setup assumes nothing secret and nothing irreplaceable lives in the folder Claude can
see. No identified data, no credentials or API keys. It defends against bad-but-recoverable
outcomes; it does not defend against leaked PII or a published key.
