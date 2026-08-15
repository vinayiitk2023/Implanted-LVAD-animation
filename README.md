# Implanted LVAD Animation

A 3D animation of a Left Ventricular Assist Device (LVAD) implanted in the human heart, modeling realistic blood flow through the ventricle and outflow cannula. The visualization captures flow patterns and shear stress distribution relevant to pump performance and thrombogenic risk.

## Contents

- `model.glb` — 3D animated model (binary glTF) of the implanted LVAD with simulated flow conditions

## Purpose

This repository hosts the `.glb` file so it can be linked directly (via its raw file URL) and embedded on a webpage using Google's [`<model-viewer>`](https://modelviewer.dev/) web component.

## Usage

To embed this model on a webpage:

```html
<script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>

<model-viewer
  src="https://raw.githubusercontent.com/vinayiitk2023/Implanted-LVAD-animation/main/model.glb"
  alt="3D model of an LVAD implanted in the heart, showing simulated blood flow through the device and ventricle"
  autoplay
  camera-controls
  auto-rotate
  style="width: 100%; height: 500px;">
</model-viewer>
```

## License

No license — all rights reserved.
