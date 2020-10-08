---
author: Jasper Van der Jeugt
date-accepted: N/A
discussion: https://github.com/haskell-org/committee/pull/1
---

# Haskell.org proposals

In an effort to make the work of Haskell.org committee more transparent, we
would like to adopt a proposal process similar to the [GHC Steering Committee].

[GHC Steering Committee]: https://github.com/ghc-proposals/ghc-proposals

The proposed process is fairly light:

1.  New proposals are created as pull requests with a single file, following
    a `proposals/XYZW-some-title.extention` naming scheme.  A template is
    available in `proposals/0000-template.md`.

2.  Proposals must have an author set who is responsible for driving the
    discussion.  If the author is not a member of the Haskell.org committee,
    we may additionally appoint a shepherd from the committee to help with this.

3.  We strive to make unanimous decisions, but we can use a majority vote (the
    committee has an odd number of members) to move forward.

4.  What happens next depends on whether or not the proposal is accepted:

     -  If the proposal is accepted, `date-accepted` is set and the proposal is
        merged into the repository.  A summary with a link to the full PR
        discussion is sent out to `community@haskell.org`.

     -  If the proposal is not accepted, the proposal is also merged for
        posterity, but a section is ammended to explain why it was rejected.
