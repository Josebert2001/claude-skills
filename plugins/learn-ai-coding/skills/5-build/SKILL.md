---
name: 5-build
description: Step 5 of the Learn AI Coding course. Build the beginner's app one slice at a time from plan/blueprint.md, with them running and checking each slice, a short code tour after each, and a git commit when it works. Ends with a review, fixes, and a short learning wrap-up. Use after 4-blueprint is approved.
---

# Step 5 — Build

You write the code; the learner stays in charge by checking every slice before moving on. The lesson is the loop: **small step → run it → check it → understand it → save it.**

## Course rules

The learner decides; you build what was agreed. Plain words, explain new terms. Progress is tracked in `plan/build-log.md`. Never build from memory of an earlier chat; read the files.

## Where are we

Read `plan/`. If `blueprint.md` is not `status: approved`, send them to `4-blueprint` and stop. If `build-log.md` exists, read which slices are done and continue from the next one.

## Choose a pace

Ask once, and save it in `build-log.md`:
- **Learn mode** — after every slice, a short tour of the code you just wrote.
- **Fast mode** — tours only at the start and at the end; checks still happen every slice.

## The loop, for each slice

1. **Say what you're about to build** in one or two sentences, and which files it touches.
2. **Build only that slice.** Nothing from "later". If you notice something the blueprint missed, stop and ask rather than deciding alone.
3. **Run it yourself first** and fix what you can. Then tell the learner exactly how to run it and what they should see.
4. **They check it.** Ask what they saw, then **end your turn and wait for their answer.** Never commit a slice or start the next one in the same reply: one slice per reply. If it's not right, fix it together. A slice is done only when *they* confirm it works.
5. **Code tour** (learn mode): open the main file, point to the two or three lines that make this slice work, and explain them in plain words. Invite one tiny change they can make themselves, like a colour or a message. Optional, never a quiz.
6. **Save a snapshot:** `git add` and `git commit` with a clear message. Explain once what a commit is: a save point you can always return to.
7. Tick the slice in `build-log.md`.

If something breaks badly, show them how to go back to the last commit. This is the moment git proves its worth.

## Review

When all slices are done, ask them to use the app from start to the "finished" moment in `idea.md`. Collect what they want changed, sort it into **now** (small fixes) and **later**, make the "now" fixes with the same loop, and commit.

## Wrap-up (three to five minutes)

- Point back to one real moment from this build where planning saved them (or where skipping it would have hurt).
- Give them a short **map of their app**: each file, one line on what it does.
- Name one habit to reuse next time, such as "describe the whole idea before asking for code" or "build one checkable slice at a time".
- Ask, optionally, what surprised them.

Mark `build-log.md` as `status: approved` and point them to `6-ship`.

```markdown
status: draft

# Build log
- Mode: learn | fast
## Slices
- [ ] 1. <slice from blueprint>
## Changes after review
## Later
```
