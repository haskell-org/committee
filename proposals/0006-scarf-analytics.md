---
author: Tikhon Jelvis
date-accepted: 2023-07-14
discussion: https://github.com/haskell-org/committee/pull/13
---

# Use Scarf to collect analytics for Haskell.org pages

## Background

We want to understand how people are using the haskell.org home page and related resources ("Getting Started", "Downloads"... etc) while respecting the privacy of site visitors. We've [moved away from Google Analytics][ga] out of concerns with privacy and compliance, and now we plan to move to a privacy-respecting alternative.

Specifically, we want to use [Scarf Gateway][scarf] on the pages under Haskell.org managed directly by the Haskell.org committee. Scarf Gateway is GDPR-compliant out of the box; more details are available under the Scarf Gateway section of [Scarf's privacy policy][scarf-privacy].

## Policy

The Haskell.org committee will start using Scarf to track visitor metrics for Haskell.org. The committee will be able to view information collected through Scarf and to delegate access to others.

[ga]: https://github.com/haskell-infra/www.haskell.org/pull/268
[scarf]: https://about.scarf.sh/scarf-gateway
[scarf-privacy]: https://about.scarf.sh/privacy-policy
