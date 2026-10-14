# Bozhao Li

Personal homepage: [wee733.github.io](https://wee733.github.io/).

The page introduces my interests and selected work in robot learning, control,
aerial robotics, simulation, and scene reconstruction. It includes public software,
research projects whose code is not public, and accompanying demonstrations.

## Contents

- B2ARX whole-body learning, deployment, and skiing simulation
- ARX manipulation and demonstration generation
- B2ARX perception and navigation
- Joint aircraft / gimbal visual landing
- RGB-D and monocular scene reconstruction
- Actuator and aircraft system identification
- CAD-to-USD docking-station simulation
- Research manuscripts and demonstrations

## Preview and maintenance

Open `index.html` directly, or serve the repository root:

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

There is no build step. GitHub Pages serves the root of `main`.
The page uses local media and `style.css`; videos load when played.

English and Chinese descriptions should stay consistent. The media
collection is under `media/web/recent/`; captions identify simulation, measured
experiments, geometry studies, and reconstruction results. Retain these distinctions
when replacing clips. Use concise captions without calendar dates. The B2 student
clip is an eight-second edit played at 2.5 times the original speed. Project summaries and media do not make private source code
public. Keep raw experiment logs, model checkpoints, resumes, and credentials out
of this repository.
