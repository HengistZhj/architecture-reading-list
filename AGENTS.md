# AGENTS.md

## Purpose
This repository is a long-term Architecture Reading List / Knowledge Base.

## Rules for Codex
When the user asks to add, edit, remove, reclassify, or update a reading:
1. Edit `books.json`.
2. Preserve valid JSON.
3. Do not redesign the website unless explicitly asked.
4. Do not delete existing readings unless explicitly asked.
5. Keep categories concise and reuse an existing category when appropriate.
6. Preserve `Primary` or `Supplementary` when the source list specifies it.
7. Priority is an integer from 1 to 5.
8. Allowed status values: `Not started`, `Reading`, `Finished`, `Reference`.
9. Add the source/library URL when one is provided. Never invent a URL.
10. Keep notes concise: one sentence explaining why the item is useful.

## Preferred data shape
{
  "title": "...",
  "authors": "...",
  "year": 2026,
  "category": "...",
  "list": "Primary",
  "priority": 4,
  "status": "Not started",
  "type": "Book",
  "notes": "...",
  "url": ""
}

## User workflow
Typical request:
"Add [book] under [category], mark it Primary, priority 5."

Make the change directly in `books.json`.
