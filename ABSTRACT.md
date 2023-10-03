Authors present a new large-scale benchmark dataset termed Aerial Imagery for Roof Segmentation (**AIRS**). This dataset provides a wide coverage of aerial imagery with 7.5 cm resolution and contains over 220,000 buildings. The task posed for AIRS is defined as *roof* segmentation. 

All the aerial images within the AOI are first merged into a single mosaic and then tiled into smaller images for better handling. The tiled images feature a size of 10000 × 10000 pixels, with a 10% overlap between adjacent tiles. As a result, the whole region is tiled into 1047 images. To facilitate research, authors split the dataset by randomly assigning the images to the following three subsets:
- *train* set. This set contains 857 images and the corresponding roof
labels for training.
- *val* set. This set contains 94 images and the corresponding
roof labels for validation.
- *test* set. This set contains 96 images for benchmark testing. Currently, for fair comparison, the corresponding roof labels are not disclosed. They will be used for evaluating the results submitted to the public challenge centered on the AIRS dataset.

![Fig_splits](https://i.ibb.co/6B1Y0Y3/Screenshot-2023-10-03-115417.png)

<i> Geographical distribution of images in: a - train set, b - val set, and c - test set of AIRS dataset.</i>

![Fig](https://i.ibb.co/RBDgPCL/Screenshot-2023-10-02-190852.png)

This figure displays the study area of the AIRS dataset. The area of interest (AOI) covers about 457 km², including almost the full area of Christchurch, the largest city in the South Island of New Zealand. The aerial imagery and the corresponding building map are open-source data provided by LINZ Data Service. The photographs were captured during the flying seasons of 2015 and 2016, and the open-source images were ortho-rectified DOMs with RGB channels and 7.5 cm resolution in the projection of New Zealand Transverse Mercator. The building footprints, which are stored as 2D polygons in a shapefile, were produced in June 2016 by manual annotation.
