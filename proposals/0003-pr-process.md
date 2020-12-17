---
author: Tikhon Jelvis
date-accepted: N/A
discussion: https://github.com/haskell-org/committee/pull/2
---

# Accepting Website PRs

To quickly triage and accept PRs to the website, we need a process for reviewing, merging and deploying changes to the website. We adopted a process for this before we had this proposal repo, and the process helped us respond to and merge PRs faster than before. This proposal codifies that process to help make our policies explicit and transparent.

Guidelines for accepting PRs to the website:

  1. Purely technical fixes—like fixing the `default.nix` file, broken links, typos and HTML glitches—require one member of the committee to approve.
  2. For uncontroversial changes that affect the content of the site, we need two committee members to approve. If the PR was authored by one or more committee members, it should be approved by *other* members unless there are less than two members not involved in the PR.
  3. Major or controversial changes require a majority vote.
  4. Changes that have known objections from anyone on the committee require a majority vote.
  
Once a PR has the approvals it requires, and assuming the change is not time-critical, the PR should stay open for at least a day to leave time for additional comments and questions. After this, the PR may be merged at any time.

Once a PR is merged, it may be deployed to the live site at any time.

A majority vote by the committee may override any of these restrictions.
