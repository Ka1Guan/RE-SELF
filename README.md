# RESELF: Seeing the World and the Self from Egocentric Video

RESELF is a project for joint metric scene reconstruction and full-body motion estimation from monocular egocentric video.

This file is a project-showcase README draft. The code is not public yet, and the release plan is listed below.

## Overview

RESELF reconstructs:
- metric scene geometry
- camera trajectory
- full-body motion of the wearer

The core idea is to couple deterministic geometry with motion generation in a shared metric frame.

## Demo Videos

These MP4s are the demo clips used in the project page.

- Cooking: [input.mp4](assets/demo_videos/sample-01-cooking/input.mp4)
- Basketball: [input.mp4](assets/demo_videos/sample-02-basketball/input.mp4)
- Soccer: [input.mp4](assets/demo_videos/sample-03-soccer/input.mp4)
- Dance: [input.mp4](assets/demo_videos/sample-04-dance/input.mp4)
- Piano: [input.mp4](assets/demo_videos/sample-05-piano/input.mp4)

## Release Plan

Nothing is publicly released yet. Planned release order:

1. Dataset package
   - EE4D-JSM release
   - aligned egocentric RGB
   - sparse metric scene geometry
   - Project Aria camera trajectories
   - SMPL-X motion
   - split files, metadata, and preprocessing scripts

2. Pretrained checkpoints
   - RESELF checkpoints
   - baseline weights

3. Code release
   - training scripts
   - evaluation scripts
   - visualization scripts

4. Documentation
   - setup instructions
   - reproducibility notes
   - data preparation guide

## Dataset

EE4D-JSM is built from EgoExo4D and EE4D-Motion and aligns egocentric RGB, sparse metric scene geometry, Project Aria camera trajectories, and SMPL-X motion under one training and evaluation protocol.

Current dataset scale:
- 16,807 training sequences
- 5,212 testing sequences
- 18 activity categories
- 70+ scenes

## Citation

```bibtex
@inproceedings{guan2026reself,
  title     = {Seeing the World and the Self from Egocentric Video},
  author    = {Guan, Kai and Jiang, Minchao and Wang, Liruichen and Zhu, Wentao and Zhang, Lei},
  booktitle = {[Conference]},
  year      = {2026}
}
```
