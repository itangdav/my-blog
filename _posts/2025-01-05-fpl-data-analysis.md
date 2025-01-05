---
layout: post
title:  "FPL Data Analysis"
date:   2025-01-05 06:10:00 -0500
categories: coding
---

Yay it's 2025! New Year will be exciting! I had some time this weekend and went back to an old project where I wanted to try to predict FPL points using basic data. Here is the repo: [repo](https://github.com/itangdav/FPLPredictor)

I'm currently just trying out different linear regressions based on recent team / opponent stats by position as well as a player's own recent stats. Since it weighs all players equally, it isn't that useful as we only really care about predicting large hauls from good players.
As a result, I currently only consider players with >=3 starts this season (up to GW19), but this still has 429 players which is a lot (realistically, I only consider <20 players per outfield position, and like only 3 players for GK). If I have time in the future, I'll probably try to tackle this first, 
before moving onto using more complex tools than just linear regression. 
