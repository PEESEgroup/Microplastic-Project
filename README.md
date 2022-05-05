# Microplastic-Project

This repository has three datasets for microplastic image analysis project. 

Microplastic image dataset has 846 microscopic images for polystyrene (355) and polyethylene (491) microbeads growing on the TEM grid over liquid-crystals sensing devices. The image heights or widths are in equivalent to 0.28 mm in real sizes. Microplastic microbeads are incubated under three different SDS concentrations (0.01 mM, 0.025 mM and 0.1 mM). Polyethylene has 162, 179 and 150 images at 0.01 mM, 0.025 mM and 0.1 mM SDS. Polystyrene has 119, 109 and 127 images at 0.01 mM, 0.025 mM and 0.1 mM SDS.

Geometric properties dataset has 160 images, which are randomly selected from microplastic image dataset. PE has 29, 26, 36 images at 0.01 mM, 0.025 mM and 0.1 mM SDS. PS has 25, 21, 23 images at 0.01 mM, 0.025 mM and 0.1 mM SDS. These selected images are employed to compute fractal dimensionality and lacunarity values. The computed geometric properties are summarized in "Geometric property.xlsx".

CAM target dataset has 402 images, with 67 images for polyethylene and polystyrene at 0.01 mM, 0.025 mM and 0.1 mM SDS. These images are the class-activation-mapping algorithm labeled region with high feature importance based on deepPolyNet CNN model. The polyethylene image heights or widths are in equivalent to 0.1 mm. The polystyrene cropped sample heights/widths are 0.07 mm in real sizes. Colorful images are processed to greyscale images for DCGAN training use.
