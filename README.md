# SealSkin concept website

A responsive student venture concept site for SealSkin. The live page presents the confirmed Mission 2 3D model in its hero area, with a static preview fallback.

SealSkin is a proposed concept, not a finished, tested, or available product. It is not for sale and does not make medical or performance claims. Review counts describe a small convenience sample; simulated discussion is not human research or proof of demand.

## Explore the model

Drag the model to rotate it. Use Front and Side for camera views, + and − to zoom, and Reset to return to the current view. The 3D concept includes the bottle, carton, cap, and label as supplied in the confirmed Mission 2 handoff. The stated 10 mL format and dimensions are approximate.

## Source project

`SealSkin-source-project.zip` contains the editable React/Vite project, including the confirmed GLB and its static preview. To rebuild:

```sh
pnpm install --frozen-lockfile
pnpm build
```

The production files are generated in `dist/`. Vite is configured for the GitHub Pages project path `/Creative-Website-/`.

If WebGL is unavailable or the model cannot load, the page shows the confirmed static preview and labels it as static.
