# smfish_pipeline
## Pipeline for Analysis of smFISH Images

### RNA
Module for segmentation of RNA and Transcription spots. Run "driver.m" function to initialize the process of segmentation, using a 16-bit z-stack of smFISH images.

### Nuclei
Module for segmentation of nuclei and assignment of RNA and transcription objects to nearest nuclei.  
"segmentation_driver.m" runs 3D connection of 2D nuclei images.
"voronoi_driver.m" creates a voronoi diagram and uses it to assign RNA and transcription objects to their nearest nuclei.

### Analysis
Functions for creating spatial bins and calculating statistics for analysis across space in discs.

This code is associated with the paper from Bakker et al., "The Wg and Dpp morphogens regulate gene expression by modulating the frequency of transcriptional bursts". eLife, 2020. http://dx.doi.org/10.7554/eLife.56076
