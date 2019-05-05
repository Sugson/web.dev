---
layout: post
title: How Best Practices scoring works
description: |
  Learn how Lighthouse calculates the Best Practices score.
---

Lighthouse returns a Best Practices score between 0 and 100.
0 is the worst possible score, and 100 is the best.

Each Best Practices audit is equally weighted.
To calculate how much each audit contributes
to your overall Best Practices score,
count the number of Best Practices audits,
then divide 100 by that number.

There's currently 14 Best Practices audits,
each audit worth 7.14 points.
Fail one audit,
and your overall Best Practices score is 92.
