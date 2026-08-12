---
name: second-brain-updater
description: Keep an existing Markdown second brain current when new material arrives. Use when someone drops a new file into their inbox and wants the brain updated. Read the new source, propose changes page by page, write a change report, wait for the exact phrase APPROVE UPDATE, and never change the original source. Do not use to build a new brain — use second-brain-builder for that.
---

# Second Brain Updater

New material arrived. Work out what it changes, and show you before changing it.

## Trigger

A new file lands in the brain's `00_Inbox/` and someone wants the brain updated.

## What I need from you

Just the brain folder. I find what is new by comparing the inbox against what the pages already say.

## Guardrails

- **I never change the file you dropped in.** It stays exactly as it arrived.
- I only touch pages inside the brain you pointed me at.
- I propose changes to **specific pages**, never "the whole brain".
- **I write nothing to a page until you type `APPROVE UPDATE`.** That exact
  phrase.
- You can approve some changes and reject others. Say which.
- **You can amend anything before approving.** Tell me the wording and I use
  yours, not mine.
- No internet, no sending, no installing, no scheduling.

## What I do

1. Read the new source and the pages it affects.
2. Write a **change report** — for each page: what I want to add, and the line
   from your source it came from. **Nothing has changed yet.**
3. You read it. Amend anything. Reject anything.
4. When you type `APPROVE UPDATE`, I apply **only** what you approved.
5. Write a **receipt** into `_meta/` — what changed, when, and from which
   source. So in six months you can ask why a page says what it says.

## The rule that matters

Your sources are the record. The brain is what I made of them.

If the two ever disagree, **the source wins** and the page is wrong. That is why I never edit sources, and why every change traces back to a line in one.
