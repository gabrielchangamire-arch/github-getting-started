# What I learned

I've been using GitHub for a while now since most of my projects live here, so a good chunk of this was review. Going back over the basics was still worth it though. It's easy to use these tools every day and never actually stop to think about what's happening underneath.

A few things that stood out:

- **Branches** clicked better for me this time, basically a safe copy to experiment in. For my own small projects I usually just work on `main`, but I get why isolating work on a branch matters once other people are in the repo.
- The **GitHub flow** (branch, commit, pull request, merge) is the habit I want to be more consistent about. Opening a PR even on my own repos is useful because it leaves a record of *why* I made a change, not just what changed.
- I keep finding new things the `gh` CLI can do compared to the web UI. Doing commits and pushes from the terminal gets a lot faster once it turns into muscle memory.

## What I'm still figuring out

- With forks I still get a bit turned around keeping things in sync with the original repo (the whole `upstream` vs `origin` thing).
- Rebase vs merge. I understand the difference on paper but I'm not always sure which one to reach for in a real situation.

## A quick markdown experiment

Inline code like `git status`, a blockquote:

> Commit early, commit often.

And a small code block:

```bash
git checkout -b my-branch
git add learned.md
git commit -m "Add notes on what I learned"
git push -u origin my-branch
```

Good refresher overall, and a reminder to actually use the workflow properly instead of committing straight to `main` like I did the first time around.
