# Microplastic-Project

This repository contains code exampls and four image/video datasets for microplastic assembly activity analysis. 

```MoDT``` contains necessary codes for the implementation of MoDT framework. It offers various functions, including object detection, segmentation, tracking, size/shape estimation, and brightness intensity characterization. Meanwhile, we also provide GradCAM++ feature importance analysis, mobility analysis (extracting diffusion coefficient and drift velocity), assembly activity analysis, and instantaneous velocity analysis algorithms for data analysis.

```Microplastic video dataset``` comprises 15-minute long brightfield optical microscope videos obtained from 8 independent experiments (4 trials for PS and 4 trials for PE) involving the adsorption of PS and PE particles onto the LC-aqueous interface. Four independent trials were conducted for each particle type. Each independent trial video consists of 6 grid squares of a single TEM grid. We obtain a total of 24 videos for each particle type (PS and PE) by extracting individual grid-squares measuring 284×284 𝜇m² from the four independent videos of both PS and PE. You can find two video examples here: https://drive.google.com/drive/folders/1utbylVJpNpkL0m9U8ztClpMG-HXIZ4FZ?usp=sharing.   

```Microplastic image dataset``` has 846 microscopic images for polystyrene (355) and polyethylene (491) microbeads growing on the TEM grid over liquid-crystals sensing devices. The image heights or widths are in equivalent to 0.28 mm in real sizes. Microplastic microbeads are incubated under three different SDS concentrations (0.01 mM, 0.025 mM and 0.1 mM). Polyethylene has 162, 179 and 150 images at 0.01 mM, 0.025 mM and 0.1 mM SDS. Polystyrene has 119, 109 and 127 images at 0.01 mM, 0.025 mM and 0.1 mM SDS.

```Geometric properties dataset``` has 160 images, which are randomly selected from microplastic image dataset. PE has 29, 26, 36 images at 0.01 mM, 0.025 mM and 0.1 mM SDS. PS has 25, 21, 23 images at 0.01 mM, 0.025 mM and 0.1 mM SDS. These selected images are employed to compute fractal dimensionality and lacunarity values. The computed geometric properties are summarized in "Geometric property.xlsx".

```CAM target dataset``` has 402 images, with 67 images for polyethylene and polystyrene at 0.01 mM, 0.025 mM and 0.1 mM SDS. These images are the class-activation-mapping algorithm labeled region with high feature importance based on deepPolyNet CNN model. The polyethylene image heights or widths are in equivalent to 0.1 mm. The polystyrene cropped sample heights/widths are 0.07 mm in real sizes. Colorful images are processed to greyscale images for DCGAN training use.

__Citations:__
Please use the following citation when using the data, methods or results of this work:

Mukherjee, F., Shi, A., You, F., & Abbott, N. L. Liquid Crystal-Driven Interfacial Organization of Colloids: Principles for Characterization of Complex Mixtures of Microplastics. Submitted to Science Advances.
