---
title: "Airbrush Snapback: Painting Directly on 3D Meshes"
excerpt: "Raycast-to-UV texture painting with spray flow, hue variation and shader-based stencil masks.<br/><img src='https://img.youtube.com/vi/FY0sdRscDPk/hqdefault.jpg' alt='' style='max-width:320px;border-radius:8px'>"
collection: portfolio
---

<div style="max-width:340px;margin:0 auto 1.5em"><div style="position:relative;padding-bottom:177.78%;height:0;overflow:hidden;border-radius:12px"><iframe src="https://www.youtube.com/embed/FY0sdRscDPk" title="Airbrush Snapback: Painting Directly on 3D Meshes" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0" loading="lazy" allowfullscreen></iframe></div></div>

A raycast from the airbrush finds the UV coordinate on the hat, and the texture is updated and reapplied every frame. Brush movement, spray radius, color flow and hue variation shape the result, while stencils are applied through a custom masking shader. Everything runs in real time on mobile hardware.

**Role:** sole developer: painting system, shaders, effects and optimization.
