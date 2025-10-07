# AgRibotLeafyVeg

AgRibot @ Bari, Italy - Leafy Vegetables (lettuce) dataset (2025)

# Dataset description
This dataset is made of natural images acquired by an Intel RealSense D435 (Santa Clara, CA, USA) RGB-D camera, in an experimental field in Bari (Apulia, Italy) of romaine lettuce (variety Romanella) .

The Intel RealSense D435 produced images of resolution of 1280x720 pixels (see color_tagID.png files), depth maps (see the depth_tagID.raw files), aligned depth maps (see the depth_aligned_tagID.raw files) of the same resolutions (units are in meters) and infrared images (see infraredLeft_tagID.png files). The plants were acquired from a top-view, at a distance between xx and xx m. Data were acquired on four dates, spaced roughly 15 days apart, throughout April and May 2025, covering an entire growing cycle from the early vegetative stage to the harvest stage. Fertilization treatments were applied on two dates between the first and second acquisition days. Four nitrogen (N) fertilization levels were considered, namely:
- N0: 0 kg/ha
- N1: 60 kg/ha
- N2: 120 kg/ha
- N3: 180 kg/ha

For each fertilization level, four repetitions were set, labeled from I to IV, resulting in a total of 16 plots. For each plot, on each experimental date, two plants were sampled and harvested for field and laboratory
analysis. The selected plants were labeled using AprilTags.

Manual annotation was performed to create a segmentation ground truth of three classes (in the Labels folder):

canopy: high vegetation other than the trunk (green segments)
grapes: grape bunches (white segments)
background: the remaining pixels (black segments)
Acknowledgments
This work was funded by the Project E-crops - Technologies for Digital and Sustainable Agriculture (Italian Ministry of University and Research, PON Agrifood Program, No. ARS01_01136).

# Credits
Annalisa Milella (CNR-STIIMA) and Giulio Reina (Politecnico of Bari) conceived and performed the experiments. Roberto Marani (CNR-STIIMA) contributed to dataset generation and maintenance. The agricultural farm Cantina San Donaci (BR), Italy, is gratefully acknowledged for hosting experimental tests and for support during data collection.

# Contact person: Annalisa Milella - annalisa.milella@cnr.it

National Research Council of Italy (CNR), Institute of Intelligent Systems and Technologies for Advanced Manufacturing (STIIMA), via Amendola 122 D/O, 70126, Bari, Italy

# Cite this dataset

