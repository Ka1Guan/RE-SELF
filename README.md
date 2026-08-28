# RESELF: Seeing the World and the Self from Egocentric Video

RESELF is a project for joint metric scene reconstruction and full-body motion estimation from monocular egocentric video.


## Overview

RESELF reconstructs:
- metric scene geometry
- camera trajectory
- full-body motion of the wearer

The core idea is to couple deterministic geometry with motion generation in a shared metric frame.

## Method

> Method figure placeholder

RESELF takes a monocular egocentric video, builds metric scene geometry with a Pi3-based backbone, and uses the recovered geometry to guide motion generation.

## Demo Video

> Full demo video placeholder

## Release Plan

Planned release items:

- [ ] Test code
- [ ] Training code
- [ ] Dataset

## Dataset

EE4D-JSM is built from EgoExo4D and EE4D-Motion and aligns egocentric RGB, sparse metric scene geometry, Project Aria camera trajectories, and SMPL-X motion under one training and evaluation protocol.

## Citation

```bibtex
@inproceedings{guan2026reself,
  title     = {Seeing the World and the Self from Egocentric Video},
  author    = {Guan, Kai and Jiang, Minchao and Wang, Liruichen and Zhu, Wentao and Zhang, Lei},
  booktitle = {[Conference]},
  year      = {2026}
}
```
