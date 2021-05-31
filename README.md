# BigBrain Hippocampus Segmentation

## BigBrain

The BigBrain is the brain of a 65 year old man with no neurological or psychiatric
diseases in clinical records at time of death. The brain was embedded in paraffin and
sectioned in 7404 coronal histological sections (20 microns), stained for cell bodies.
BigBrain is the digitized reconstruction of the hi-res histological sections 
(20 microns isotropic).

## Dataset content

This dataset contains hippocampus segmentation from the  BigBrain release 2015 
published in the [BigBrain Project website](https://bigbrainproject.org).

Surfaces are provided for CA1, CA2, CA3, CA4, dendate gyrus, subiculum, and the mid-surface.

Files are organized as follows:

- JSON/*: a complete model in JSON format (try it with [brainbrowser](https://brainbrowser.cbrain.mcgill.ca/surface-viewer#ct))

- A3D/*: these are the surface files to use with Atelier3D (you also need to download the full A3D model for the BigBrain volume and place these files in the same base directory for A3D)

- MNI-obj/*: surfaces in MNI-OBJ format

- wavefront-obj/*: surfaces in WaveFront-OBJ format

- stl/*: surfaces in STL format

- gii/*: surfaces in GIfTI format

## Reference and more information

##### Hippocampus segmentation

DeKraker, J., Lau, J.C., Ferko, K.M., Khan, A.R., Kohler, S., "Hippocampal subfields revealed through unfolding and unsupervised clustering of laminar and morphological feaures in 3D BigBrain", NeuroImage, Feb 1 2020 (DOI 10.1016/j.neuroimage.2019.116328).

##### The BigBrain

The BigBrain dataset is the result of a collaborative effort between the
teams of Dr. Katrin Amunts and Dr. Karl Zilles (Forschungszentrum Jülich)
and Dr. Alan Evans (Montreal Neurological Institute). 

Amunts, K. et al.: "BigBrain: An Ultrahigh-Resolution 3D Human
Brain Model", Science (2013) 340 no. 6139 1472-1475, June 2013.
[https://www.sciencemag.org/content/340/6139/1472.abstract](https://www.sciencemag.org/content/340/6139/1472.abstract)

For more information please visit the [BigBrain Project website](https://bigbrainproject.org).
