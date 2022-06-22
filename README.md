# Landslide4sense challenge description
The aim of the competition is to promote innovative algorithms for automatic landslide detection using remote sensing images around the globe, 
and to provide objective and fair comparisons among different methods. The competition ranking is based on a quantitative accuracy metric 
(F1 score) computed with respect to undisclosed test samples. 

# The data
The Landslide4Sense dataset is derived from diverse landslide-affected areas around the world from 2015 through 2021. It can be downloaded from: 
https://www.iarai.ac.at/landslide4sense/challenge/. 

The data consists of the training, validation, and test sets containing 3799, 245, and 800 image patches, 
respectively. Each image patch is a composite of 14 bands that include:
* Multispectral data from Sentinel-2: B1, B2, B3, B4, B5, B6, B7, B8, B9, B10, B11, B12.
* Slope data from ALOS PALSAR: B13.
* Digital elevation model (DEM) from ALOS PALSAR: B14.
All bands in the competition dataset are resized to the resolution of ~10m per pixel. The image patches have the size of 128 x 128 pixels and are labeled pixel-wise.

For this project we have followed two different approaches: 
