# AIGC paper list for a Computer Vision Engineer
A list of papers on AIGC in recent 3 years, must be read by a __Computer Vision Engineer__.

## Disclaimer
This list does not aim to be exhaustive. There are two aims of this repository: 

1.For an experienced Computer Vision Engineer, this rep records usefull papers should be read carefully and understood well;

2.For a beginner Engineer, these papers may give you an overview of AIGC in CV in rencent 3 years.

## Table of contents
- [VQ-VAE](#VQ-VAE) 
- [GAN based methods](#GAN-based-methods) 
- [3D aware GAN](#3D-aware-GAN) 
- [Nerf based methods](#Nerf-based-methods) 
- [Diffusion based methods](#Diffusion-based-methods)
- [Multi-mode methods](#Multi-mode-methods)


# Papers
## VQ-VAE
* Neural Discrete Representation Learning (VQ-VAE), NIPS 2017
* Generating Diverse High-Fidelity Images with VQ-VAE-2, NIPS 2019
* Taming Transformers for High-Resolution Image Synthesis (VQ-GAN), CVPR 2021

## GAN based methods
### General imgae genneration/edit
* Semantic Image Synthesis with SPADE, CVPR 2019
* A Style-Based Generator Architecture for Generative Adversarial Networks (StyleGAN), 2018
* Analyzing and Improving the Image Quality of StyleGAN (StyleGAN2), CVPR 2020
* Alias-Free Generative Adversarial Networks (StyleGAN3), NeurIPS 2021
* Drag Your GAN: Interactive Point-based Manipulation on the Generative Image Manifold (DragGAN), SIGGRAPH 2023

### Face swap
* SimSwap: An Efficient Framework For High Fidelity Face Swapping
* DeepFaceLab: Integrated, flexible and extensible face-swapping framework, 2020
* FaceShifter: Towards High Fidelity And Occlusion Aware Face Swapping with Pytorch-Lightning, 2019
* HifiFace: 3D Shape and Semantic Prior Guided High Fidelity Face Swapping, 2021

### Face edit
* Interpreting the Latent Space of GANs for Semantic Face Editing, TPAMI 2020
* Encoding in Style: a StyleGAN Encoder for Image-to-Image Translation, CVPR 2021
* PTI: Pivotal Tuning for Latent-based editing of Real Images, ACM TOG 2022, (pSp)
* HyperStyle: StyleGAN Inversion with HyperNetworks for Real Image Editing, CVPR 2022

### Face animation
* First Order Motion Model for Image Animation, NIPS 2019
* Pose-Controllable Talking Face Generation by Implicitly Modularized Audio-Visual Representation, CVPR 2021
* A Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild, ACM MM, 2020
* One-Shot Free-View Neural Talking-Head Synthesis for Video Conferencing, CVPR 2021
* Thin-Plate Spline Motion Model for Image Animation, CVPR 2022

### Body image genneration/edit
* InsetGAN for Full-Body Image Generation, CVPR 2022
* StyleGAN-Human: A Data-Centric Odyssey of Human Generation, ECCV 2022

## 3D aware GAN
* Efficient Geometry-aware 3D Generative Adversarial Networks (EG3D), CVPR 2022
* StyleSDF: High-resolution 3d-consistent image and geometry generation, CVPR 2022
* GRAM: Generative Radiance Manifolds for 3D-Aware Image Generation, CVPR 2022

## Nerf based methods
* Nerf: Representing scenes as neural radiance fields for view synthesis, ECCV 2020
* Implicit neural representations with periodic activation functions， 2020
* Instant Neural Graphics Primitives with a Multiresolution Hash Encoding, SIGGRAPH 2022
* Neus: Learning neural implicit surfaces by volume rendering for multi-view reconstruction, NeurIPS 2021
* Mip-nerf: A multiscale representation for anti-aliasing neural radiance fields, 2021
* Nerfies: Deformable neural radiance fields, ICCV 2021
* D-nerf: Neural radiance fields for dynamic scenes, CVPR 2021
* Nerf in the wild: Neural radiance fields for unconstrained photo collections, CVPR 2021

## Diffusion based methods
### Basic theory
* Denoising Diffusion Probabilistic Models (DDPM), NIPS 2020
* Denoising Diffusion Implicit Models (DDIM), 2021
* Classifier-Free Diffusion Guidance, 2022

### 2D image
* Diffusion Models Beat GANs on Image Synthesis, 2021
* High-Resolution Image Synthesis with Latent Diffusion Models, CVPR 2022
* Scalable Diffusion Models with Transformers, 2022

### Conditional image generation
* Palette: Image-to-Image Diffusion Models, 2021
* Prompt-to-Prompt Image Editing with Cross Attention Control, 2022
* Dreambooth: Fine tuning text-to-image diffusion models for subject-driven generation, CVPR 2023
* An Image is Worth One Word: Personalizing Text-to-Image Generation using Textual Inversion, 2022
* Lora: Low-rank adaptation of large language models, ICLR 2022
* Adding Conditional Control to Text-to-Image Diffusion Models, 2023

### 3D content genneration
* DreamFusion: Text-to-3D using 2D Diffusion, 2022
* ProlificDreamer: High-Fidelity and Diverse Text-to-3D Generation with Variational Score Distillation, 2023

### Video generation
* Video Diffusion Models, 2022

## Multi-mode methods
* Learning Transferable Visual Models From Natural Language Supervision (CLIP), 2021
* GLIDE: Towards Photorealistic Image Generation and Editing with Text-Guided Diffusion Models, 2021
* Hierarchical Text-Conditional Image Generation with CLIP Latents (DALL-E 2), 2022
* Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding (Imagen), 2022
* InstructPix2Pix: Learning to Follow Image Editing Instructions, CVPR 2023


