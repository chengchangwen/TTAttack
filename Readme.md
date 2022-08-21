## Introduction

This is an official release of the paper **Universal, Transferable Adversarial Perturbations for Visual Object Trackers**.
![images](./images/teaser.png)

**Abstract.** In recent years, Siamese networks have led to great progress in visual object tracking. While these methods were shown to be vulnera- ble to adversarial attacks, the existing attack strategies do not truly pose great practical threats. They either are too expensive to be performed online, require computing image-dependent perturbations, lead to unre- alistic trajectories, or suffer from weak transferability to other black-box trackers. In this paper, we address the above limitations by showing the existence of a universal perturbation that is image agnostic and fools black-box trackers at virtually no cost of perturbation. Furthermore, we show that our framework can be extended to the challenging targeted attack setting that forces the tracker to follow any given trajectory by us- ing diverse directional universal perturbations. At the core of our frame- work, we propose to learn to generate a single perturbation from the object template only, that can be added to every search image and still successfully fool the tracker for the entire video. As a consequence, the resulting generator outputs perturbations that are quasi-independent of the template, thereby making them universal perturbations. Our exten- sive experiments on four benchmarks datasets, i.e., OTB100, VOT2019, UAV123, and LaSOT, demonstrate that our universal transferable per- turbations (computed on SiamRPN++) are highly effective when trans- ferred to other state-of-the-art trackers, such as SiamBAN, SiamCAR, DiMP, and Ocean online.
