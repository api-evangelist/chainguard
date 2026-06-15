---
title: "Chainguard Artifacts Safe from Miasma Phantom Gyp npm Attack"
url: "https://www.chainguard.dev/unchained/chainguard-artifacts-safe-from-miasma-phantom-gyp-npm-attack"
date: "2026-06-05"
author: ""
feed_url: "https://www.chainguard.dev/unchained/rss.xml"
---
On June 3, 2026, attackers published 286 malicious versions across 57 npm packages, deploying a self-replicating CI/CD worm that harvests credentials and spreads itself using a novel install-time execution technique hidden within binding.gyp files that most security tools overlook. The attack targeted packages with significant download volumes, including one SDK pulling approximately 408,000 monthly downloads. Chainguard's architecture blocked this supply chain worm, protecting customers through design, and all Chainguard artifacts remain safe from this attack.
