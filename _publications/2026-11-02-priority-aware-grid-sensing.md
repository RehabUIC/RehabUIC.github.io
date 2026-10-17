---
title: "Priority-Aware Grid Sensing for Scalable Heterogeneous Multi-Robot Coordination"
collection: publications
category: conferences
permalink: /publication/2026-11-02-priority-aware-grid-sensing
excerpt: 'A shared-policy MARL framework that embeds task relevance into each robot&apos;s observation and scales to ten robot and task types, where the standard Unity ML-Agents grid sensor fails to learn.'
date: 2026-11-02
venue: 'IEEE International Conference on Tools with Artificial Intelligence (ICTAI 2026), Boca Raton, Florida (accepted)'
citation: 'Shawon, R. U., &amp; Liu, S. (2026). &quot;Priority-Aware Grid Sensing for Scalable Heterogeneous Multi-Robot Coordination.&quot; <i>IEEE International Conference on Tools with Artificial Intelligence (ICTAI 2026)</i>. Accepted.'
---

Coordinating robot teams gets harder as the number of robot and task types grows. This paper introduces a priority-aware grid sensor that embeds task relevance directly into each robot's observation, letting a single shared policy coordinate heterogeneous teams.

* Evaluated in Unity across heterogeneous, sequential, and collaborative task settings (126 training runs over 3-, 5-, and 10-type configurations).
* At 10 robot and task types, the method reached cumulative training rewards of 445.1 (heterogeneous), 366.1 (sequential), and 273.5 (collaborative), while the default Unity ML-Agents grid sensor stayed near zero.
* Policies generalized to unseen task sequences (71.0–71.9% accuracy) and unseen collaboration requirements (81.0–86.2%, versus 85.6% on the trained ones) without retraining.
