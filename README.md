# BA/SA Take-Home Task

This is an interactive take-home task for the Senior BA/SA position. Instead of a document to fill out, you'll work through it step by step with Claude as your guide.

---

## Before you start

**You'll need a GitHub account to submit your work.** If you haven't already sent your GitHub username to the person who sent you this task — do that now, before you begin. They'll add you as a collaborator so your submission goes through without issues at the end.

No GitHub account? Let the person who sent this know and they'll find an alternative.

---

## What you'll need

- **Claude Code** — the CLI tool from Anthropic. Install it at [claude.ai/code](https://claude.ai/code). You'll need a free account.
- **Git** — to clone this repo and submit your work

---

## Setup

```bash
# 1. Clone this repo
#    Use the link from the email or message you received — it's specific to you.
git clone <your-repo-link>
cd <repo-folder>

# 2. Open Claude Code in this folder
claude .
```

Once Claude Code opens, type:

```
/ba-task
```

Claude will take it from there.

---

## How it works

The task has 13 steps. At each step, Claude explains what we're looking for, you respond, and Claude may ask follow-up questions before moving on. Your answers get saved as files in the `submissions/` folder as you go.

You can use any tools you want — including AI — while working through the steps. Claude will ask about that too.

---

## Submitting

At the end of the task, Claude will give you the exact commands to submit:

```bash
git checkout -b submission/your-name
git add submissions/
git commit -m "BA task submission — Your Name"
git push origin submission/your-name
```

Then send the branch name (or PR link) to the person who sent you this task.

**Getting a permission error when pushing?** Your GitHub username wasn't added yet. Reply to the person who sent you this with your username — they'll add you and you can run the push command again. Your work is saved locally, nothing is lost.

---

Any technical issues with setup? Reach out before starting — don't lose time on tooling.
