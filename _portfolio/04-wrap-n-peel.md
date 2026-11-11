---
title: "Wrap N Peel: Cloth, Mesh Extraction and Real-Time Textures"
excerpt: "Vinyl wrapping on car parts: cloth simulation baked into meshes, normal-map editing and mask-based cutting.<br/><img src='https://img.youtube.com/vi/qjZHQ0h8Rh0/hqdefault.jpg' alt='' style='max-width:320px;border-radius:8px'>"
collection: portfolio
---

<div style="max-width:340px;margin:0 auto 1.5em"><div style="position:relative;padding-bottom:177.78%;height:0;overflow:hidden;border-radius:12px"><iframe src="https://www.youtube.com/embed/qjZHQ0h8Rh0" title="Wrap N Peel: Cloth, Mesh Extraction and Real-Time Textures" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0" loading="lazy" allowfullscreen></iframe></div></div>

Cloth interacts with the car body, then its simulated shape is extracted into a static mesh that conforms to the geometry. Wrinkles live in a normal map that the squeegee tool rewrites pixel by pixel, so smoothing needs no mesh recalculation. Cutting tracks the tool path into a mask, a custom shader splits the mesh along it, and the excess can be peeled off. All of it runs in real time on mobile.

**Role:** sole programmer: cloth, mesh processing, texture manipulation, shaders and optimization.
