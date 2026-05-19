# Developer Velocity

**Know how your team ships.** Developer Velocity is a lightweight, zero-backend tool that gives you instant visibility into your team's pull request and code review activity across GitHub repos.

No servers. No sign-ups. No data leaves your browser.

---

## What It Does

Drop in a GitHub token, pick your repos and date range, and get a clear breakdown of:

**📦 Pull Requests**
- How many PRs each person submitted and merged
- Lines of code merged
- Average time to merge

**👀 Peer Reviews**
- How many PRs each person reviewed
- Average time to first review
- Comment volume and actioned comments

Everything is grouped **per user, per month** — so you can spot trends and celebrate wins.

**🔍 Click any cell** to open an overlay with the full list of related pull requests — so you can drill into the details behind every number.

---

## Getting Started

It's just one HTML file. Seriously.

1. Open `developer-velocity.html` in any modern browser
2. Paste your GitHub token
3. Enter repos (like `myorg/api, myorg/frontend`) — or leave blank to scan all your private repos
4. Pick a date range
5. Hit **Get Developer Velocity** and watch the magic happen ✨

---

## GitHub Token Setup

You'll need a **fine-grained Personal Access Token** → [Create one here](https://github.com/settings/tokens?type=beta)

Grant it **read-only** access to:

| Permission     | Access    |
|----------------|-----------|
| Code           | Read-only |
| Metadata       | Read-only |
| Pull requests  | Read-only |

That's it. Minimal permissions, maximum insight.

> 🔒 Your token is only used to call the GitHub API directly from your browser. It's never stored or sent anywhere else.

---

## Why This Exists

Engineering leads and teams deserve simple, private tooling to understand delivery patterns — without installing yet another SaaS platform or granting org-wide OAuth access to a third party.

This is one file you can bookmark, share on Slack, or drop into your team wiki.
