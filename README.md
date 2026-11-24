# AI DJ — Alternate Setup

An alternate snapshot of the camera-based music player prototype.

**Repository created:** 2022-11-06  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2022-11-06

## Features and implementation

- Two bundled audio tracks.
- P5.js audio loading.
- Webcam capture.
- PoseNet initialization.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, p5.sound, ml5.js, PoseNet.

## Project structure

| File | Purpose |
| --- | --- |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`style.css`](style.css) | Page styling |

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/try2forAI-DJ-App.git
cd try2forAI-DJ-App
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Open the prototype and inspect model initialization.

## Current status and limitations

The pose callback and music-selection draw loop are not included.

## Related project snapshots

Other repositories in this project family:
- [AI_DJ_Project1](https://github.com/Avenger-Sonic123/AI_DJ_Project1) — repository created 2022-10-26
- [AI-DJ-WebApp2](https://github.com/Avenger-Sonic123/AI-DJ-WebApp2) — repository created 2022-11-06
- [AI-DJ2](https://github.com/Avenger-Sonic123/AI-DJ2) — repository created 2022-11-22
- [AI-DJ-Webapp-Project](https://github.com/Avenger-Sonic123/AI-DJ-Webapp-Project) — repository created 2022-11-24

---

Source reference: [`e15654da`](https://github.com/Avenger-Sonic123/try2forAI-DJ-App/tree/e15654da0893a7ae146d8d3e38807e0a68e91ee7) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
