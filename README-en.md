<div align="center">

[English](README_en.md) | [中文](README.md)

</div>

# UE5.6+ StarterContent Add-on Pack

## Introduction

Since Unreal Engine 5.6, the StarterContent beginner content pack is no longer included by default when creating a new project. This repository provides the complete official StarterContent pack, which you can import directly into your UE project.

It includes basic materials, static meshes, particle effects, props, basic shapes, common textures, and two sample maps (StarterMap and Advanced_Lighting), making it ideal for beginners to learn, quickly prototype scenes, and test lighting setups.

## Folder Structure

The archive contains a `StarterContent` folder at its root. After extracting it into your project's Content directory, the structure fully matches the official layout:

```
Content/
└── StarterContent/
    ├── Materials/
    ├── Meshes/
    ├── Particles/
    ├── Props/
    ├── Shapes/
    ├── Textures/
    └── Maps/
        ├── StarterMap
        └── Advanced_Lighting
```

## Installation Steps

1. **Fully close your UE project** to avoid asset loading conflicts or material issues
2. Download the `StarterContent.zip` archive
   - If the archive is distributed via **Releases**, download the latest version from the **Releases** page of this repository
3. Open your UE project's root directory and enter the `Content` folder
   - Reference path: `YourProjectName/Content/`
4. Extract `StarterContent.zip` into the current `Content` directory
   - After extraction, a complete `StarterContent` subfolder will appear under `Content`
5. Reopen your UE project — you will see all the StarterContent assets in the Content Browser

## Notes

- Compatible with UE 5.6 / 5.7 and above; also works with UE 5.0–5.5
- If your project already contains a `StarterContent` folder with the same name, back it up before overwriting
- If assets appear red/missing after opening the project, right-click the `StarterContent` folder in the Content Browser and select **Reimport**, or restart the project
