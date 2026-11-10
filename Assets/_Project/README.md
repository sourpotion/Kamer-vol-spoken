# Professional VR Unity project structure

This archive preserves the original Assets content and adds a clean, studio-style
workspace under `Assets/_Project/`.

## Existing project
The supplied project already contains a Unity VR Template, XR Interaction Toolkit
3.1.2 assets, XR/OpenXR settings, TextMesh Pro assets, sample scenes and URP
configuration. Those original files have deliberately been left in their original
locations so existing Unity GUID references, scene links and package sample paths
are not broken.

## New workspace
Use `Assets/_Project/` for your own game content. Keep imported package/sample
content in its existing locations or in a clearly named third-party area.

Folder guide:
- Art: models, materials, textures, shaders, VFX and sprites
- Audio: music, sound effects, ambience and voice
- Prefabs: reusable game objects, including VR prefabs
- Scenes: core, menu, levels, environments and test scenes
- Scripts: gameplay, player, VR, interaction, UI and systems
- Settings: project-owned rendering, XR, input and quality assets
- RenderTextures, Lighting, PostProcessing, Animation and Timeline: technical content
- UI and Data: interface assets and project data
- Tests: edit-mode and play-mode tests
- Documentation: project notes and technical documentation

## Important
This is an organization scaffold, not a migration of existing assets. Move existing
assets into `_Project` only deliberately, using Unity's Project window so Unity
updates references. Do not delete the original `Scenes`, `Settings`, `XR`, `XRI`,
`VRTemplateAssets`, `Samples` or `TextMesh Pro` folders.
