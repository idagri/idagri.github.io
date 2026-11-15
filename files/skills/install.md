# Installing the Claude Skills

Six skills from my own Claude setup, generalized for any researcher. Each zip holds one skill
folder: its main file `SKILL.md`, the reference files it reads, any scripts it runs, and an MIT
`LICENSE`.

- `conference-guide.zip`: Conference Guide
- `bib-check.zip`: Citation Check
- `close-chat.zip`: Chat Close-Off
- `code-audit.zip`: Code Audit
- `paper-to-markdown.zip`: Paper to Markdown
- `ocr-scans.zip`: OCR for Scans

`claude-skills-all.zip` holds every skill folder at its root, so in Claude Code
`unzip claude-skills-all.zip -d ~/.claude/skills/` installs all of them. The Claude app takes one
skill per upload, so use the single-skill zips there.

## Claude Code (Recommended)

1. Unzip the skill's zip.
2. Move the folder into `~/.claude/skills/`, so its main file sits at
   `~/.claude/skills/<skill-name>/SKILL.md`. To use a skill in one project only, put the folder in
   that project's `.claude/skills/` instead.
3. Open a new chat, since skills load when a chat starts, and ask for the task in your own words,
   for example "check the citations in paper.tex" or "plan my schedule for this conference program".

## Claude in the Browser or the Desktop App's Chat

1. Turn on code execution: Settings, then Capabilities, then "Code execution and file creation".
2. Go to Customize, then Skills, click "+", choose "Create skill", then "Upload a skill", and upload
   the zip as it is (do not unzip it).
3. Start a new chat and ask for the task.

The chat version does not keep files between chats, so a skill gives you its settings as a file at
the end of its first run. Attach that file to later chats, or add it to a Claude Project's
knowledge. Steps that run on folders of your own computer (the close-off scan, a rerun in the code
audit, the PDF read hook, the conference guide's multi-agent ranking) need Claude Code.

## First Run and Settings

Each skill asks a few questions the first time it runs: your website and CV for the conference
guide, your citation-key convention for the citation check, where your notes and handoffs live for
the close-off, where to keep the markdown copies of papers, and the budget for image work for the
OCR skill. It shows you the answers before
saving them in `~/.claude/<skill-name>/`, outside the skill folder, so installing a newer version
keeps them. To change them later, ask the skill to update its settings.

## Requirements by Skill

- Conference Guide: Python 3 with matplotlib and PyMuPDF, and a TeX installation with `xelatex`. On
  a Mac it uses Arial, and elsewhere it uses DejaVu Sans, which matplotlib includes. The email
  search is optional and needs a connected email tool, such as the Gmail connector.
- Citation Check: internet access for Crossref, OpenAlex and publisher pages. Key renames end in a
  compile, so they need BibTeX or biber and pdflatex.
- Chat Close-Off: Python 3 for its scan, and git if your project uses it. The zip also holds
  `references/claude_md_rules.md`, a short block of rules you can paste into your own `CLAUDE.md`
  so every chat keeps its record in files. The first run offers to add it.
- Code Audit: the software your project runs (Stata, R or Python) for reruns in an original
  project. A replication package is read without running unless you ask for a rerun.
- Paper to Markdown: Python 3.10 or newer. The first run sets up the converter, pymupdf4llm (about
  110 MB to download), in its own environment under `~/.claude/paper-to-markdown/`. In Claude Code
  it also offers an optional read hook: a check Claude Code runs before each file read, set by one
  entry in `~/.claude/settings.json`, that sends every paper PDF Claude opens to its stored copy. `references/read_hook.md` in the zip shows the entry,
  how to test it and how to remove it, and the hook lets a read through unchanged whenever anything
  goes wrong.
- OCR for Scans: Python 3.9 or newer with PyMuPDF and Pillow (`pip install pymupdf pillow`).
  `pdfimages` from poppler is optional. In the Claude app chat, attach the page images or the PDF
  if Claude cannot open the pages it renders.

## Updating a Skill

Replace the skill folder with the one from the new zip. Your settings stay where they are.

## License

MIT: free to use, change and share, with the license file kept in each copy.
