# ModularToolKit_Plugin
A portable plug-and-play library for rapid material prototyping and rendering setup.

💡 Why this exists?
Moving between projects in Unreal Engine often involves the pain of migrating folders, fixing broken paths, and re-creating basic shaders from scratch. I built this plugin to serve as a portable source of truth — a "Reference Manual" that I can plug into any new project to get up and running in seconds.

🛠 What’s Inside?
1. The Generic Master Material
A robust, all-in-one shader template that covers 90% of surface needs. Instead of complex inheritance, I use it as a Node Template — simply copy the logic into a local material to ensure zero dependencies if the plugin is detached.

Full PBR Support: Base Color, Metallic, Specular, Roughness/Glossiness, Emissive, Opacity.

Advanced Maps: Normal/Height, Ambient/Reflection, Refraction/IOR.

UV & Animation: Tiling, Texture Rotation, Displacement (Vertex Offset), and Texture Movement (Panning).

2. Special FX Shaders
Animated Emissive: A custom material with "shimmering/pulsing" logic. Great for UI, magic effects, or tech props.

3. Rendering Cheat Sheet
Pre-configured settings and sample counts for high-quality rendering. No more guessing the "baseline" quality — just a quick reference to ensure consistent output every time.

🚀 Workflow
Drop & Enable: Add to the Plugins folder and activate.

Reference & Copy: Open the Master Material, copy the optimized node blocks, and paste them into your project-specific materials.

No Dependencies: Since nodes are copied, your project stays clean and independent of the plugin in the long run.
