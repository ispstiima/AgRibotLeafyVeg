# AgRibotLeafyVeg

AgRibot @ Bari, Italy - Leafy Vegetables (lettuce) dataset (2025)

# Dataset description
This dataset is made of natural images of a lettuce crop (Lactuca sativa L. var Longifolia, cultivar Tercius RZ) acquired using an Intel RealSense D435 (Santa Clara, CA, USA) RGB-D camera, in an experimental field in Bari (Apulia, Italy).

The dataset includes color (RGB) images (see the color_tagID.png files), color images aligned to depth (see the color_aligned_tagID.png files), depth maps (see the depth_tagID.raw files) and depth maps aligned to the color stream (see the depth_aligned_tagID.raw files). All images have a resolution of 1280x720 pixels. Depth maps are provided in millimeters. 

The plants were acquired from a top-view, approximately at a distance between 0.9 and 1.3 m from the ground. Data were acquired on four dates, spaced roughly 15 days apart, throughout April and May 2025, covering the entire growing cycle from the early vegetative stage to the harvest stage. Fertilization treatments were applied on two dates between the first and second acquisition days. Four nitrogen (N) fertilization levels were considered, namely:
- N0: 0 kg/ha
- N1: 60 kg/ha
- N2: 120 kg/ha
- N3: 180 kg/ha

For each fertilization level, four replications were set, labeled from I to IV, resulting in a total of 16 plots. For each plot, on each experimental date, two plants were sampled and harvested for field and laboratory
analysis. The selected plants were labeled using AprilTags (see tagID in filenames).

For each sample plant the corresponding plant mask is provided (see the plant_mask_tagID.png files), with white pixels corresponding to plant pixels and black pixels corresponding to the background or other plants. This mask is obtained in a semi-automated manner by using a SAM2 segmenter (https://ai.meta.com/sam2/) with manual bounding box input on the color images.

# Acknowledgement
This work was funded by the project AgRibot-Harnessing Robotics, XR/AR, and 5G for a New Era of Safe, Sustainable, and Smart Agriculture, European Union’s Horizon Europe research and innovation programme (Grant Number: 101183158).

# Credits


# Contact person: 
Dr. Annalisa Milella, PhD
annalisa.milella@cnr.it


# Cite this dataset

