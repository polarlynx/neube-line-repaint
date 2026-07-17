<a id="english"></a>

<h1 align="center">NeuBE Line Repaint</h1>

<p align="center">
  Re-render image material as clean, inspectable line trajectories.
</p>

<p align="center">
  <a href="https://neubeart.com/"><strong>Official Website</strong></a>
  ·
  <a href="https://cn.neubeart.com/"><strong>中文官网</strong></a>
  ·
  <a href="https://github.com/polarlynx/neube-line-repaint/issues"><strong>Issues</strong></a>
</p>

<p align="center">
  <img src="docs/assets/hero-before.webp" width="49%" alt="Original colorful character image">
  <img src="docs/assets/hero-after.webp" width="49%" alt="Re-rendered trajectory result">
</p>

NeuBE Line Repaint is a desktop creative tool that reconstructs sketches, AI concepts, screenshots, renders, backgrounds, and commercial art as cleaner line trajectories. Instead of simply exposing source-image edges, it re-renders the visible structure into a more coherent result that artists can inspect, edit, composite, and hand off.

This repository is a public project page. The application source code is not included here.

## Visual Results

### Design Workspace

<table>
  <tr>
    <td width="50%"><img src="docs/assets/desk-source.webp" alt="Designer desk source image"></td>
    <td width="50%"><img src="docs/assets/desk-rendered.webp" alt="Re-rendered designer workspace trajectory"></td>
  </tr>
  <tr>
    <td align="center"><strong>Source image</strong></td>
    <td align="center"><strong>Re-rendered result</strong></td>
  </tr>
</table>

### Game Prop Sheet

<table>
  <tr>
    <td width="50%"><img src="docs/assets/game-source.webp" alt="Game asset workbench source image"></td>
    <td width="50%"><img src="docs/assets/game-rendered.webp" alt="Re-rendered game prop trajectory"></td>
  </tr>
  <tr>
    <td align="center"><strong>Source image</strong></td>
    <td align="center"><strong>Re-rendered result</strong></td>
  </tr>
</table>

### Commercial And Illustration Material

<table>
  <tr>
    <td width="25%"><img src="docs/assets/tea-source.webp" alt="Botanical tea source image"></td>
    <td width="25%"><img src="docs/assets/tea-rendered.webp" alt="Re-rendered botanical packaging trajectory"></td>
    <td width="25%"><img src="docs/assets/storybook-source.webp" alt="Storybook deer source image"></td>
    <td width="25%"><img src="docs/assets/storybook-rendered.webp" alt="Re-rendered storybook illustration trajectory"></td>
  </tr>
  <tr>
    <td align="center">Packaging source</td>
    <td align="center">Re-rendered result</td>
    <td align="center">Illustration source</td>
    <td align="center">Re-rendered result</td>
  </tr>
</table>

## What It Focuses On

- **Re-rendered line trajectories** that reconstruct visible structure instead of merely tracing source-image edges.
- **Readable structure** for characters, props, interiors, UI-like scenes, packaging, and textured illustration.
- **Editable handoff direction** for PNG and PSD-style workflows.
- **Noise reduction** around soft, painterly, or uneven source edges.
- **Local-first workflow** shaped like a desktop art tool.

## Ongoing Development

NeuBE will keep improving around real creative work—not metered cloud usage.

- **Next priorities:** a more natural drawing feel, stronger sketch repainting, more useful color extraction, and the workflow details surfaced by real projects.
- **Shaped by feedback:** feature requests, edge cases, and production feedback shared in [GitHub Issues](https://github.com/polarlynx/neube-line-repaint/issues) help set the direction of each update.
- **Updates beyond the license:** the drawing workspace and bundled local Stable Diffusion tools continue to receive updates without an active license.
- **No usage economy:** beyond the license you choose, there are no generation credits, usage packs, or second subscription layer.
- **Local-first by design:** creative work and processing stay on your machine.

### R&D Concept Previews — In Development

> The following concept visuals communicate active R&D directions. They are not features in the current release and do not promise a specific release date.

#### Stronger Low-Resolution Recovery

Improve structural recovery and line clarity when the source image is small, soft, or visibly pixelated.

<p align="center">
  <img src="docs/assets/roadmap/low-resolution-recovery.webp" width="100%" alt="Concept preview of low-resolution input recovery from pixelated source to clean linework">
</p>

#### Advanced Color Separation

Explore editable separation for gradients, hidden accent colors, multiply shading, and richer color relationships.

<p align="center">
  <img src="docs/assets/roadmap/advanced-color-separation.webp" width="100%" alt="Concept preview of gradients, hidden colors, multiply shadows, and highlights separated into editable layers">
</p>

#### Editing-Friendly Vector Conversion

Explore converting raster artwork into editing-friendly vector paths, shapes, and logical object groups.

<p align="center">
  <img src="docs/assets/roadmap/editable-vector-conversion.webp" width="100%" alt="Concept preview of raster artwork converted into editable vector paths and object groups">
</p>

## PSD-Oriented Output

<p align="center">
  <img src="docs/assets/psd-proof.webp" width="72%" alt="PSD proof with an editable trajectory layer stack">
</p>

NeuBE Line Repaint is designed around re-rendered trajectories that can keep moving through a production pipeline. The goal is not just a preview image, but a cleaner editable layer that can be checked, adjusted, composited, and handed off.

## Good Fits

- AI concept art that needs cleaner line structure.
- Commercial art and packaging concepts.
- Prop sheets and game asset workbenches.
- Backgrounds and interior scenes with readable perspective.
- Screenshot-like design scenes with panels, tools, and small details.

## Known Limits

Very soft painterly sources, dense exterior street scenes, and ambiguous texture edges can still require manual review or cleanup. The best results come from source images where the main shapes and details are visually readable.
