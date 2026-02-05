# Cliff Scene – Breakdown

A warm sunset cliff overlooking the ocean – dense atmospheric fog, layered clouds, subtle cinematic lighting, and rich sound design (waves, wind, birds). The goal was to balance readability, scale, and atmosphere while staying physically plausible in HDRP.

---

## 1. Blockout

<p align="center">
  <img src="Breakdown\Unity_I33mUKXeA8.png" alt="Cliff preview" />
</p>

**Goals:**

- Define main camera framing
- Establish horizon line and cliff silhouette
- Place primary focal points (cliff edge, ocean, sky)
- Rough scale relationships (cliff height vs water vs sky)

**Notes:**

- Simple primitives only
- No lighting yet beyond default sky

---

## 2. Terrain & Grass

<p align="center">
  <img src="Breakdown\Unity_pS0QvIzl6L.png" alt="Cliff preview" />
</p>

**What was done:**

- Sculpted base terrain shape in Unity Terrain tools
- Pass of macro shapes → erosion → micro detail
- Grass placement driven by height + slope masks
- Gradient falloff toward cliff edges for realism

**HDRP considerations:**

- Wind zone tuned for subtle motion
- Density balanced for performance

> **Assets:**
>
> - **[HDRP Surfaces Starter Pack](https://assetstore.unity.com/packages/2d/textures-materials/hdrp-surfaces-starter-pack-239445)** – by **Ravibio**
> - **[Grass Flowers Pack Free](https://assetstore.unity.com/packages/2d/textures-materials/nature/grass-flowers-pack-free-138810)** – by **ALP**

---

## 3. Rockwork

<p align="center">
  <img src="Breakdown\Unity_XcKZOwkBmV.png" alt="Cliff preview" />
</p>

**Technical workflow:**

- Original textures converted to HDRP-compatible Mask Maps using **[MaskMapWizard](https://github.com/cfrBernard/maskmapwizard)** and **[Materialize](http://boundingboxsoftware.com/materialize/)**

**Art pass:**

- Larger hero rocks placed first
- Secondary rocks used to break repetition
- Variation in scale, rotation, and erosion wear

> **Assets:**
>
> - **[Rock and Boulders 2](https://assetstore.unity.com/packages/3d/props/exterior/rock-and-boulders-2-6947)** – by **Manufactura K4**

---

## 4. Props

<p align="center">
  <img src="Breakdown\Unity_Z4iy5ZXxH6.png" alt="Cliff preview" />
</p>

**Workflow:**

- All textures converted to HDRP with **[MaskMapWizard](https://github.com/cfrBernard/maskmapwizard)**
- Placement focused on:
  - Guiding the eye toward the horizon
  - Adding foreground depth
  - Breaking the cliff silhouette
  
**Composition notes:**

- Avoided symmetry
- Clustered smaller props for visual interest

> **Assets:**
>
> - **[Cracked Tree Trunk](https://assetstore.unity.com/packages/3d/vegetation/trees/cracked-tree-trunk-277007)** – by **Aliosa**
> - **[Dream Tree 2 (HDRP)](https://assetstore.unity.com/packages/3d/vegetation/trees/dream-tree-2-hdrp-316919)** – by **IL.ranch**
> - **[Rock and Boulders 2](https://assetstore.unity.com/packages/3d/props/exterior/rock-and-boulders-2-6947)** – by **Manufactura K4**

---

## 5. HDRP Water

<p align="center">
  <img src="Breakdown\Unity_MnLaC3mWsr.png" alt="Cliff preview" />
</p>

**Setup:**

- HDRP Water System (Sea)
- Shoreline foam enabled and tuned
- Wave deformation adjusted for scale and mood
- Water color shifted warmer to match sunset lighting
- Reflections balanced to avoid over-bright highlights

**Key tweaks:**

- Foam intensity increased near the cliff base
- Wave normal scale reduced for a calmer sea
- Horizon haze blended into volumetric fog

---

## 6. FX & Sound

<p align="center">
  <img src="Breakdown\Unity_mqkwnodx8v.png" alt="Cliff preview" />
</p>

**Lighting support:**

- Soft **fill light** added to:
  - Improve rock readability
  - Separate props from background fog
  - Keep the scene cinematic (low intensity, large area)

**Sound design:**

- Layered ambience:
  - Ocean waves (loop + distant crashes)
  - Wind over cliff
  - Distant birds

**Birds VFX:**

- Real-time flock using VFX Graph
- Subtle random pathing + turbulence
- Looping flight pattern across the horizon

> **Tutorial reference:** https://www.youtube.com/watch?v=2tA0qwihLPs&t=179s

---

## 7. Global Volume & Lighting

<p align="center">
  <img src="Breakdown\Unity_bG9WbkPTbH.png" alt="Cliff preview" />
</p>

**Lighting:**

- Directional Light (sun) at low angle (golden hour)
- Slightly warm temperature
- Soft shadow bias for natural contact shadows

**Volumetrics:**

- Volumetric Fog:
  - Higher density near horizon
  - Gradual falloff toward camera
- Cloud layers:
  - Slow-moving volumetric clouds
  - Breaks in clouds to create god-ray hints (subtle)

**Post-processing:**

- Filmic tonemapping
- Gentle vignette
- Slight bloom on sun highlights
- Color grading toward warm/cinematic look

---

<p align="center">
  <img src="Preview.png" alt="Cliff preview" />
</p>

> This scene was as much about **atmosphere and readability** as it was about pure realism. The heavy fog + sunset created strong mood, while careful lighting and fill lights ensured the cliff and props remained clear and visually appealing.

---

<br>

<div align="center">

[![Hub](https://img.shields.io/badge/◀-Hub-blue?style=for-the-badge)](../../README.md)
[![Profile](https://img.shields.io/badge/◀-Profile-green?style=for-the-badge)](https://github.com/cfrBernard)

</div>