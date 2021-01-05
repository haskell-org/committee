---
author: Tikhon Jelvis
date-accepted: N/A
discussion: https://github.com/haskell-org/committee/pull/3
---

# Accepting Website PRs

To quickly triage and accept PRs to the website, we need a process for reviewing, merging and deploying changes to the website. We adopted a process for this before we had this proposal repo, and the process helped us respond to and merge PRs faster than before. This proposal codifies that process to help make our policies explicit and transparent.

Guidelines for accepting PRs to the website:

  1. Purely technical fixes—like fixing the `default.nix` file, broken links, typos and HTML glitches—require one member of the committee to approve.
  2. Uncontroversial changes that affect the content of the site need two committee members to approve. If the PR was authored by one or more committee members, it should be approved by *other* members unless there are less than two members not involved in the PR.
  3. Major changes (eg removing whole pages, a visual redesign) and controversial changes (eg removing options from the downloads page) need a majority vote of the whole committee.
  4. Changes that have known objections from anyone on the committee require a majority vote.
  
A PR may be merged once it has the approvals it requires and it has been at least 24 hours since the last substantial change. Time-critical PRs like security fixes may be merged without the 24 hour requirement.

Once a PR is merged, it may be deployed to the live site at any time.

A majority vote by the committee may override any of these restrictions.
