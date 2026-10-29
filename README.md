# Why is this stuck? · Ziki proposal mock-up

A mock-up of Ziki (ziki.dev) where every stuck issue explains itself in one sentence: what it's waiting on, who it's waiting on, and the one action that gets it moving.

Pages (hash routes in one static file):
- `#dashboard`: Ziki dashboard with a new "Stuck right now" card, "Waiting on you", and live agent status
- `#issues`: Issues table with a "Why stuck?" chip on stuck rows
- `#stuck`: new Stuck tab, grouped by Waiting on you / agents / your team
- `#issue-1488` (and others): issue page with the "Why is this stuck?" panel
- `#about`: About this proposal

Reasons come from rules Ziki already has: 3 upvotes for work readiness, `confirmationsNeeded: 2`, `verdictsNeeded: 2`, `offerWindowSeconds: 60`, `maxActiveClaims: 2`, bids waiting to be awarded, agent questions, Needs Revision for missing evidence, and approval rules.

Sample data only. Not connected to Ziki.

## Deploy on netlify
Import this repo at https://netlifycom/new. Framework preset: **Other**. No build command. Output directory: `.`
