# Meadow Scene – Breakdown

A calm, open meadow at golden hour – light, airy, and gentle. This was my **first HDRP scene in Unity**, so the focus was mainly on learning the pipeline, lighting, and basic world-building rather than heavy technical complexity.

---

## 1. Terrain & Grass

<p align="center">
  <img src="Breakdown\Unity_xORDNnZ23f.png" alt="Meadow preview" />
</p>

**What was done:**

- Sculpted a simple rolling landscape with a few soft hills in the background
- One larger hill on the left, placed to frame the main red tree -
 Clean, readable horizon line

**Grass:**

- Large coverage of animated grass across the meadow
- Wind zone tuned for visible, flowing motion (very organic look)
- **Performance note:** this pass is quite heavy – minimal optimization here as this was an early learning scene

**Composition:**

- Mostly open space in the foreground to let the light and atmosphere breathe
- Subtle elevation changes to avoid a flat plane

---

## 2. Props

<p align="center">
  <img src="Breakdown\Unity_rluQmKkKSM.png" alt="Meadow preview" />
</p>

**Assets & placement:**

- Hero **red tree** placed on the left hill – main focal point
- A smaller secondary tree placed far right to balance the frame
- Scattered rocks and small plants to add scale and break repetition
- Props kept sparse to maintain the peaceful, open meadow feel

**Art notes:**

- Avoided clutter – the scene relies more on light and mood than asset density
- Props used mainly for depth layering rather than detail overload
- Rock textures converted to HDRP with **[MaskMapWizard](https://github.com/cfrBernard/maskmapwizard)**

> **Assets:**
>
> - **[Flowers And Garden Assets](https://assetstore.unity.com/packages/3d/vegetation/flowers/flowers-and-garden-assets-241214)** – by **MARCIN'S ASSETS**
> - **[Dream Tree 2 (HDRP)](https://assetstore.unity.com/packages/3d/vegetation/trees/dream-tree-2-hdrp-316919)** – by **IL.ranch**
> - **[Rock and Boulders 2](https://assetstore.unity.com/packages/3d/props/exterior/rock-and-boulders-2-6947)** – by **Manufactura K4**

---

## 3. FX & Sound

<p align="center">
  <img src="Breakdown\Unity_qwO5qVpIzh.png" alt="Meadow preview" />
</p>

**VFX:** 

- 🦋 Butterfly VFX (Shader Graph)
  - One flock in the **foreground** for immediate depth
  - One flock flying **closer to the red tree** to guide the eye
  - Slow, natural flight paths with gentle turbulence

**Environment FX:**

- Grass reacting to wind (global wind zone)
- Subtle movement across the whole meadow for a “living” feel

**Sound design:**

- Soft ambient wind
- Distant birds chirping
- Light rustling of grass

> The overall audio intention was calm and relaxing — no dramatic or harsh elements.

---

## 4. Global Volume & Lighting

<p align="center">
  <img src="Breakdown\Unity_FVDrstaKP0.png" alt="Meadow preview" />
</p>

**Lighting:**

- Directional Light positioned low for **golden hour**
- Sun aligned roughly toward camera, passing through the red tree branches
- Warm color temperature for a cozy sunset feel
- Clean, soft shadows – not too harsh

**Atmosphere:**

- Very little volumetric fog compared to the **[Cliff scene](../Env_002_Cliff/README.md)**
- Clearer air to emphasize light rays and lens flare
- Horizon kept crisp and readable
- Volumetric clouds

**Post-processing:**

- Gentle bloom around the sun
- Subtle lens flare for cinematic touch
- Light filmic tonemapping
- Warm color grading, but lighter and more natural than the **[Cliff scene](../Env_002_Cliff/README.md)** *(more bluish)*

---

<p align="center">
  <img src="Preview.png" alt="Meadow preview" />
</p>

> This scene is simpler and more “classic” than the [Cliff](../Env_002_Cliff/README.md) – it’s more about **light, space, and mood** than technical complexity. As an early HDRP piece, it was mainly a playground for: 
> - learning HDRP lighting, 
> - understanding global volumes, 
> - and seeing how grass, wind, and basic VFX behave together.

---

<br>

<div align="center">

[![Hub](https://img.shields.io/badge/◀-Hub-blue?style=for-the-badge)](../../README.md)
[![Profile](https://img.shields.io/badge/◀-Profile-green?style=for-the-badge)](https://github.com/cfrBernard)

</div>