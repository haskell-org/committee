---
author: Julian Ospald
date-accepted: N/A
discussion: https://github.com/haskell-org/committee/pull/8
---

# Haskell download page simplification

## Motivation

The download page has been a frequent source of confusion as was discussed
[here](https://github.com/haskell-infra/www.haskell.org/issues/12).

The last major overhaul was discussed and merged [here](https://github.com/haskell-infra/www.haskell.org/pull/71). To further simplify the download page, another discussion was started [here](https://github.com/haskell-infra/www.haskell.org/pull/93).

Despite all these efforts, the download page continues to be a rather overloaded
and confusing landing page.

## Solution

I propose to:

1. Make https://www.haskell.org/downloads/ redirect to https://www.haskell.org/ghcup/
2. Create a separate repository for the ghcup homepage sources, which currently lives at https://gitlab.haskell.org/haskell/ghcup-hs/-/tree/master/www
3. Create a wiki page, e.g. on [ghcup wiki](https://gitlab.haskell.org/haskell/ghcup-hs/-/wikis/Other-installation-options) about other installation options, which can be adjusted more easily by users
4. Adjust ghcup homepage to link to the wiki page and the newly created repository

## Rationale

1. The last missing piece of simplifying instructions were missing windows and missing stack support from GHCup. These issues have been fixed and further work is ongoing to make the experience even smoother.
2. A separate repository for ghcup homepage seems reasonable, so the haskell.org committe has better visibility and users can raise issues and PRs with the committee.
3. A wiki page is more dynamic for alternative installation options. Users can participate here more easily.
