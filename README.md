# Unity-Scene-Showcase

A showcase of **Unity scenes built in HDRP**, focusing on lighting, atmosphere, composition, and reproducible workflows.This repository is both a **visual portfolio** and a **technical breakdown** of how each scene was built – from blockout to final polish.

---

## What you’ll find here

- High-quality **HDRP scenes**
- Step-by-step **visual breakdowns** of each scene
- Notes on **lighting, atmosphere, water, and composition**
- Links to the **tooling** that supports my workflow (Python / C#)

---

## Meadow Scene
![Unity](https://img.shields.io/badge/Unity-6000.1.12f1-blue?logo=unity&logoColor=white)

<p align="center">
  <img src="Scenes\Env_001_Meadow\Preview.png" alt="Meadow preview" />
</p>

**[View full breakdown →](Scenes/Env_001_Meadow/README.md)**
> *Simple scene, natural lighting, volumetric fog, landscape design, and VFX.*

---

## Cliff Scene

![Unity](https://img.shields.io/badge/Unity-6000.1.12f1-blue?logo=unity&logoColor=white)

<p align="center">
  <img src="Scenes\Env_002_Cliff\Preview.png" alt="Cliff preview" />
</p>

**[View full breakdown →](Scenes/Env_002_Cliff/README.md)** 
> *Natural lighting, volumetric fog, landscape design, and HDRP water, and VFX.*

---

> More scenes to come...

---

## My Tools

Much of my workflow for these scenes is supported by custom tools.

### 🐍 Python Tools

- **MaskMapWizard** – This is a simple Python interface, designed to help you create Mask Maps by combining multiple textures (such as Metallic, AO, Detail, and Smoothness) into a single RGBA image.

    🔗 https://github.com/cfrBernard/MaskMapWizard

### 🔧 Unity / C# Tools

- **UnityTimelapse** – Simple script designed to quickly create timelapses in Unity HDRP. Ideal for presenting scenes, cinematics, or testing lighting variations without using Timeline.
    
    🔗 https://github.com/cfrBernard/UnityTimelapse

---

## Technical Overview

- **Render Pipeline:** HDRP

- **Primary Lighting Model:** Physically Based Exposure

- **Key Features Used:**
    - Volumetric Fog
    - Contact Shadows
    - HDRP Water System
    - Screen Space Reflections
    - Custom Post-Processing stacks

> More detailed technical settings are documented per scene.

---

## Contact

If you’re interested in the scenes, tooling, or collaboration – feel free to open an issue or reach out.
