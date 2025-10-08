# AgRibotLeafyVeg

AgRibot @ Bari, Italy - Leafy Vegetables (lettuce) dataset (2025)

# Dataset description
This dataset is made of natural images of Lactuca sativa L., cv. Romanella acquired using an Intel RealSense D435 (Santa Clara, CA, USA) RGB-D camera, in an experimental field in Bari (Apulia, Italy).

The Intel RealSense D435 produced color (RGB) images (see the color_tagID.png files), color images aligned to depth (see the color_aligned_tagID.png files), depth maps (see the depth_tagID.raw files), depth maps aligned to the color stream (see the depth_aligned_tagID.raw files) and infrared images (see infraredLeft_tagID.png files). All images have a resolution of 1280x720 pixels. Depth maps are provided in millimeters. 

The plants were acquired from a top-view, approximately at a distance between 0.9 and 1.3 m from the ground. Data were acquired on four dates, spaced roughly 15 days apart, throughout April and May 2025, covering an entire growing cycle from the early vegetative stage to the harvest stage. Fertilization treatments were applied on two dates between the first and second acquisition days. Four nitrogen (N) fertilization levels were considered, namely:
- N0: 0 kg/ha
- N1: 60 kg/ha
- N2: 120 kg/ha
- N3: 180 kg/ha

For each fertilization level, four repetitions were set, labeled from I to IV, resulting in a total of 16 plots. For each plot, on each experimental date, two plants were sampled and harvested for field and laboratory
analysis. The selected plants were labeled using AprilTags (see tagID in filenames).

For each sample plant the corresponding plant mask is provided (see the plant_mask_tagID.png files), with white pixels corresponding to plant pixels and black pixels corresponding to the background or other plants. This mask is obtained in a semi-automated manner by using a SAM2 segmenter (https://ai.meta.com/sam2/) with manual bounding box input on the color images. For reflectance calibration, images of the reflectance calibration targets in both the visible and infrared spectra are included. 

# Acknowledgement
This work was funded by the project AgRibot-Harnessing Robotics, XR/AR, and 5G for a New Era of Safe, Sustainable, and Smart Agriculture, European Union’s Horizon Europe research and innovation programme (Grant Number: 101183158).
Project website: https://agribot-project.eu/

# Credits
Annalisa Milella (CNR-STIIMA) and Giulio Reina (Politecnico of Bari) conceived and performed the experiments. Arianna Rana and Antonio Petitti (CNR-STIIMA) contributed to dataset generation and maintenance. Francesco Montesano (UNIBA) contributed to the experimental design and field setup. Sysman Progetti & Servizi S.r.l. is gratefully acknowledged for hosting experimental tests and for support during data collection.

# Contact person: 
Annalisa Milella - annalisa.milella@cnr.it, National Research Council of Italy (CNR), Institute of Intelligent Systems and Technologies for Advanced Manufacturing (STIIMA), via Amendola 122 D/O, 70126, Bari, Italy

# Cite this dataset

