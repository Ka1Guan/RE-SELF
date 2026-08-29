<div align="center">

# Seeing the World and the Self from Egocentric Video

RESELF: REconstructing the Scene and the sELF.

Kai Guan<sup>1,2,*</sup>, Minchao Jiang<sup>2,*</sup>, Liruichen Wang<sup>2</sup>, [Wentao Zhu](https://wentao.live/about.html)<sup>2,†</sup>, [Lei Zhang](https://www4.comp.polyu.edu.hk/~cslzhang/)<sup>1,†</sup>

<sup>1</sup>The Hong Kong Polytechnic University &nbsp;&nbsp; <sup>2</sup>Eastern Institute of Technology, Ningbo  
<sup>*</sup>Equal contribution &nbsp;&nbsp; <sup>†</sup>Corresponding authors

[Project Website](https://ka1guan.github.io/RESELF)

</div>

RESELF is a project for joint metric scene reconstruction and full-body motion estimation from monocular egocentric video.

## 📌 TODO

- [ ] Release the test code
- [ ] Release the training code
- [ ] Release the dataset

## 🎬 Overview

RESELF jointly reconstructs metric scene geometry and the wearer's full-body motion from monocular egocentric video. The pipeline follows three steps:

- Metric geometry: reconstruct the surrounding scene and camera trajectory in a shared metric frame.
- Conditioned motion: predict full-body motion conditioned on the recovered geometry.
- Kinematic feedback: refine pose and camera consistency with closed-loop feedback.

![Method figure](assets/fig_inference.png)


## 📂 Dataset

EE4D-JSM is built from [EgoExo4D](https://ego-exo4d-data.org/) and [EE4D-Motion](https://github.com/chaitanya100100/UniEgoMotion/blob/main/DATASET.md). It aligns egocentric RGB, sparse metric scene geometry, Project Aria camera trajectories, and SMPL-X motion for training and evaluation.

## 📧 Contact

If you have any questions, feel free to contact: kai11.guan@connect.polyu.hk

## 🤝 Acknowledgments

This project is built upon [Pi3](https://github.com/yyfz/Pi3) and [UniEgoMotion](https://chaitanya100100.github.io/UniEgoMotion/).

## 📝 Citation

```bibtex
@inproceedings{guan2026reself,
  title     = {Seeing the World and the Self from Egocentric Video},
  author    = {Guan, Kai and Jiang, Minchao and Wang, Liruichen and Zhu, Wentao and Zhang, Lei},
  booktitle = {[Conference]},
  year      = {2026}
}
```
