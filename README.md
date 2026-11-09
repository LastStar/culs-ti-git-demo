# Git and GitHub demo

EIEC4E / INFOAN1 · Theoretical Informatics · Lecture 6 · 10 November 2026

The repository for the "Part 2: Git and GitHub" demo in the [lecture deck](https://github.com/pepe/present-star/blob/master/presentations/Theoretical-Informatics.md).
In it you add two observations to `NOTES.md` and record them as two separate commits.

## Get a copy you can write to

You cannot push to this repository. On GitHub choose **Fork**, then clone your fork:

```sh
git clone https://github.com/<your-account>/culs-ti-git-demo.git ti-demo
cd ti-demo
git status
git remote -v
git branch --show-current
```

Expect the remote `origin` pointing at your fork, and the branch `main`.

## The demo

1. Add `Git commits the staged content.` to `NOTES.md` and stage it with `git add NOTES.md`.
2. Add `Pushing shares commits with a remote.` and leave it unstaged.
3. Commit the staged line, push, and find the commit on GitHub.
4. Stage, commit and push the second line.

Before each step, check where the change is with `git status --short`, `git diff -- NOTES.md` and `git diff --cached -- NOTES.md`.
