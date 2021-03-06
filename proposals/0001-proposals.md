---
author: Jasper Van der Jeugt
date-accepted: 2020-11-15
discussion: https://github.com/haskell-org/committee/pull/1
---

# Haskell.org proposals

In an effort to make the work of Haskell.org committee more transparent, we
would like to adopt a proposal process similar to the [GHC Steering Committee].

[GHC Steering Committee]: https://github.com/ghc-proposals/ghc-proposals

## Scope

The proposal process applies for all areas that are under Haskell.org's purview.
More information about what that includes can be found on the
[Haskell.org committee page].

[Haskell.org committee page]: https://www.haskell.org/haskell-org-committee/

We don't want to introduce too much administrative overhead, so small changes,
fixes and maintenance can be made to the website and infrastructure without a
proposal.  However, we will use proposals for anything else:

 -  major and/or controversial changes
 -  setting policy for anything Haskell.org is responsible
 -  any other important decisions

## Process

The proposed process is fairly light:

1.  New proposals are created as pull requests with a single file, following
    a `proposals/XYZW-some-title.extension` naming scheme.  A template is
    available in `proposals/0000-template.md`.

2.  Proposals must have an author set who is responsible for driving the
    discussion.  If the author is not a member of the Haskell.org committee,
    we may additionally appoint a shepherd from the committee to help with this.
    It is the responsibility of the author and the shepherd to notify any
    communities that may be interested in the proposal, so we can gather
    community feedback.

3.  The proposal must have a link to the PR discussion, so readers can easily
    find the full discussion once the PR is merged.

4.  We strive to make unanimous decisions, but we can use a simple majority
    vote (the committee has an odd number of members) to move forward.

5.  What happens next depends on whether or not the proposal is accepted:

     -  If the proposal is accepted, `date-accepted` is set and the proposal is
        merged into the repository.  A summary with a link to the full PR
        discussion is sent out to `community@haskell.org`.  The proposal should
        be updated with the votes and possibly arguments against the proposal.

     -  If the proposal is not accepted, the proposal is also merged for
        posterity, but a section is ammended to explain why it was rejected.

## Resolution

This proposal was accepted by a 6/7 majority on 15 November 2020:

 -  Alexandre Garcia de Oliveira
 -  Emily Pillmore
 -  George Wilson
 -  Jasper Van der Jeugt
 -  Rebecca Skinner
 -  Tikhon Jelvis

It was discussed on the `community@haskell.org` mailing list here:

 -  <https://mail.haskell.org/pipermail/haskell-community/2020-October/000393.html>
 -  <https://mail.haskell.org/pipermail/haskell-community/2020-November/000398.html>
