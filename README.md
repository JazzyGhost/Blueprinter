<div align="center">
  <img src="https://github.com/user-attachments/assets/b6da3aad-f53e-4bac-aa41-6ec56deb30b7" width="200" />
  <h1>Blueprinter</h1>
  <p><i>3D Modeling, Simplified. Blueprinting, Reimagined.</i></p>
  
  <img src="https://github.com/user-attachments/assets/c970c2ad-382c-4fdc-b29d-a42e3e0bd02f" width="100%" />
</div>
<img width="1396" height="898" alt="Screenshot 2026-03-13 040422" src="https://github.com/user-attachments/assets/58b872de-598d-4655-ade5-58ff001d373a" />
<img width="1400" height="903" alt="Screenshot 2026-03-13 040244" src="https://github.com/user-attachments/assets/0b3abd66-126f-4d96-b3f2-75ae37bd38f6" />
</div>
<img width="1398" height="902" alt="Screenshot 2026-03-13 040109" src="https://github.com/user-attachments/assets/4a08b5a5-722e-4c77-9951-c6555019cd35" />
</div>
---

Welcome! Blueprinter is an app I made because I was too lazy to learn Blender. This app has several basic functions, and a Tool Server which lets you create and run plugins natively. Blueprinter, of course is free and plugin dependent. The goal is that anyone can download the base app to make basic objects/scenes, or create/download tools and plugins that really enhance the app. Anything can be added- more shapes, menus, functions, colors, and even brushes or sculpting.

If you plan on using the provided plugins or using the base version of Blueprinter, then you can skip installation instructions and just download and run the setup. If you intend on downloading/using any third-party plugins/tools, then I am not liable for any damages. The current version is windows only, I will work on a mac build if there is enough interest. The plugins that I have provided are already integrated in the app, one is a template that teaches you how to build a plugin, and the other is a screenshot plugin to show the basic setup of a functional plugin.

I intend on making future releases to Blueprinter, mostly to the amount of shapes that can be created, maybe an object finder/explorer list, and some other stuff. Below I've listed the full functionality of the app:

</div>

Installation:
- Install and run "Blueprinter Setup.exe"
- Optionally, download the provided plugins or create your own
- Launch Blueprinter and setup your tools

NOTE FOR CREATING PLUGINS/ PLUGIN SETUP:
- Place all plugins within the Blueprinter directory, and make sure the plugin is able to communicate with the tool server (localhost:3001 is the default address) - check plugintemplate.py

</div>

3D & 2D Modeling
Parametric Primitives: Spawn Cubes, Planes, Triangles, Hexagons, and Pentagons.

Dynamic Geometry: Use sliders to change polygon counts in real-time (e.g., turning a square into a circle by increasing segments).

Face-Level Coloring: Advanced "Face Mode" using raycasting to select and paint individual faces of a 3D object independently.

3D/2D Typography: Render custom text as physical 3D geometry or flat 2D labels within your scene.

Precision Tools
Magnet Snap: A dedicated "Snap-to-Grid" toggle for pixel-perfect object alignment.

Custom Color Lab: A full RGB color wheel and brightness slider, plus 10 saved custom paint slots for consistent branding.

Grid Architect: Complete control over X/Y grid visibility, scaling, and positional offset to match any project scale.

Extensibility
Local Tool Server: An integrated Node.js server that listens for external Python scripts on a customizable IP and Port.

Python Plugin Support: Includes a plugintemplate.py for community-made mods, automation, and external integrations (like LM Studio).

Automated Gallery: A built-in screenshot tool that captures your project and organizes thumbnails into a sleek in-app Gallery.

Export & Compatibility
Native Project Files: Save and load your work as .blue (JSON) files to keep your geometry parameters editable.

Game Engine Exports: One-click export to .GLB (GLTF) and .OBJ for seamless use in Blender, Unity, Unreal Engine, and Godot

Optional Files:
- PluginTemplate.py - A plugin template (read it and it tells you how to build plugins)
- Test_Screenshot.py (Recommended) - Simple screenshot and Gallery plugin (adds "Gallery" to settings and "Camera" icon next to the dark-mode toggle switch.
