# ModularToolKit_Plugin
A portable plug-and-play library for rapid material prototyping and rendering setup.

💡 Why this exists?

Moving between projects in Unreal Engine often involves the pain of migrating folders, fixing broken paths, and re-creating basic shaders from scratch. I built this plugin to serve as a portable source of truth — a "Reference Manual" that I can plug into any new project to get up and running in seconds.

🛠 What’s Inside?

1)The Generic Master Material

A robust, all-in-one shader template that covers 90% of surface needs. Instead of complex inheritance, I use it as a Node Template — simply copy the logic into a local material to ensure zero dependencies if the plugin is detached.

Base Color

Metallic

Specular

Roughness/Glossiness

Emissive

Opacity

Normal/Height

Ambient/Reflection

Refraction/IOR.

Also:
Tiling, Texture Rotation, Displacement and Texture Movement (Panning).

<br>

2)Animated Emissive Material
I added a material with iridescent emissive, which I just like and find useful.

<br>

3)Rendering Cheat Sheet
Basic settings for rendering, sample settings, so you don't forget which samples to use for basic quality

<br>

🚀 Workflow
Drop & Enable: Add to the Plugins folder and activate.

Reference & Copy: Open the Master Material, copy the optimized node blocks, and paste them into your project-specific materials.

No Dependencies: Since nodes are copied, your project stays clean and independent of the plugin in the long run.
