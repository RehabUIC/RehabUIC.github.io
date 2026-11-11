---
title: "Fruitful Plucking: Hierarchical Custom Physics"
excerpt: "A procedurally generated tree that bends and springs back as fruits are pulled.<br/><img src='https://img.youtube.com/vi/zUmArY4JGmY/hqdefault.jpg' alt='' style='max-width:320px;border-radius:8px'>"
collection: portfolio
---

<div style="max-width:340px;margin:0 auto 1.5em"><div style="position:relative;padding-bottom:177.78%;height:0;overflow:hidden;border-radius:12px"><iframe src="https://www.youtube.com/embed/zUmArY4JGmY" title="Fruitful Plucking: Hierarchical Custom Physics" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0" loading="lazy" allowfullscreen></iframe></div></div>

Instead of engine joints, the tree is a rig-like hierarchy where forces propagate through parent-child links. The mesh and UVs are generated procedurally and skinned to that structure. Pulling a fruit builds tension through the branches until it detaches and the energy releases, at a fraction of the cost of joint-based physics.

**Role:** sole developer: custom physics, procedural mesh generation, particles and optimization.
