---
name: 6-ship
description: Step 6 of the Learn AI Coding course. Help a beginner publish their finished app to a public GitHub repository safely, record a short demo video, and write a README in their own words. Use after 5-build is done.
---

# Step 6 — Ship

Finishing means someone else can see it. This step puts the project on GitHub and gets a short demo recorded. The learner writes their own words about their project; you help them check it, not write it for them.

## Course rules

Plain words, one step at a time. The learner owns their description of the project: you may ask questions to help them say it and fix spelling and grammar, but never write or rewrite it for them.

## Where are we

Read `plan/`. If `build-log.md` is not `status: approved`, send them to `5-build` and stop.

## 1. Safety check before publishing

Public means anyone in the world can read it. Before pushing, check together:
- No passwords, API keys or tokens in any file or in past commits (`git log -p` and search for words like `key`, `secret`, `password`, `token`). If any were ever committed, explain they must be changed at the provider, because deleting the file does not remove it from history.
- `.env` and `plan/profile.md` are in `.gitignore` and not tracked (`git ls-files`).
- Nothing personal they wouldn't want public.

## 2. Put it on GitHub

Walk them through it, explaining each step once:
- Create a new **public** repository on GitHub (website, or `gh repo create` if they have the GitHub CLI).
- Connect and push: `git branch -M main`, `git remote add origin <url>`, then `git push -u origin main`.
- Open the repository page together and check the files are there.

## 3. The README, in their words

Ask them to write a few lines: what it is, who it's for, how to run it. Interview them if they're stuck ("How would you explain it to a friend?"), then fix only spelling and grammar. Add the run instructions from `blueprint.md` underneath, which you may write. Commit and push.

## 4. The demo video

Help them plan a video of one to two minutes: open the app, show the main journey, end on the "finished" moment from `idea.md`. Suggest their system's built-in screen recorder (on Windows, Win + Alt + R or the Snipping Tool; on Mac, Cmd + Shift + 5). They can upload it to YouTube as unlisted, or add it to the repository.

## 5. Optional: put it online

Only if they want others to try it directly. For a plain web page, GitHub Pages is the simplest. Explain it as an extra, not a requirement.

## Finish

Congratulate them specifically: name the thing that makes their app theirs. Remind them of the "later" lists in `idea.md` and `build-log.md`: that is their next project, and they can run the same six steps on it.
