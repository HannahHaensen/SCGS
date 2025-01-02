# Semantics-Controlled Gaussian Splatting for Outdoor Scene Reconstruction and Rendering in Virtual Reality

## Authors
Hannah Schieber, Jacob Young, Tobias Langlotz, Stefanie Zollmann, Daniel Roth

## Abstract
Advancements in 3D rendering like Gaussian Splatting (GS) allow novel view synthesis and real-time rendering in virtual reality (VR). However, GS-created 3D environments are often difficult to edit. For scene enhancement or to incorporate 3D assets, segmenting Gaussians by class is essential. Existing segmentation approaches are typically limited to certain types of scenes, e.g., ''circular'' scenes, to determine clear object boundaries. However, this method is ineffective when removing large objects in non-''circling'' scenes such as large outdoor scenes. We propose Semantics-Controlled GS (SCGS), a segmentation-driven GS approach, enabling the separation of large scene parts in uncontrolled, natural environments. SCGS allows scene editing and the extraction of scene parts for VR. Additionally, we introduce a challenging outdoor dataset, overcoming the ''circling'' setup. We outperform the state-of-the-art in visual quality on our dataset and in segmentation quality on the 3D-OVS dataset. We conducted an exploratory user study, comparing a 360-video, plain GS, and SCGS in VR with a fixed viewpoint. In our subsequent main study, users were allowed to move freely, evaluating plain GS and SCGS. Our main study results show that participants clearly prefer SCGS over plain GS. We overall present an innovative approach that surpasses the state-of-the-art both technically and in user experience.

## Code
Code will be release with the paper publication.

VR Code: we will provide the Unreal Code for the main user study for comparability. If for example, one creates a better representation integratable into Unreal it would be comparable to SCGS.

Gaussian Splatting training code, we adapted the rasterizer and will provide the training code with the paper publication.

TBA

## Dataset

[Link to OSF](https://osf.io/s9uvy/?view_only=eff198d8752840e69a9f2b8c1c10b0a0)


![image](https://github.com/HannahHaensen/SCGS/blob/gh-pages/docs/assets/dataset.png?raw=true)

Our approach was compared with [Gaussian Grouping](https://github.com/lkeab/gaussian-grouping)

We also tested other online available code for example: [gaussian_semantics](https://github.com/shahanneda/gaussian_semantics). For Gaussian Semantics we compared the OpenSea scene resulting in PSNR of 27.85 and SSIM of 0.840 compared to ours with a PSNR of 28.85 and SSIM of 0.840.

Moreover, we compared segmentation quality to the state of the art on 3D OVS.

