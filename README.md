# Modified K-Means for Image Segmentation
Modifies the traditional k-means clustering algorithm to consider spatial information when assigning clusters. 


![Image of Output](/README_image.png)

## Getting Started
### Prerequisites
- Download modules: 
  - scipy
    - `conda install -c anaconda scipy`
  - pillow
    - `conda install -c anaconda pillow`
  - numpy
    - `conda install -c anaconda numpy`
  - matplotlib
    - `conda install -c conda-forge matplotlib`
- File(s):
  - modified_kmeans_segmentation.ipynb
  - test_img.jpg

### Running
- In the cell under "SET THESE VARIABLES", set:
  - "img_name" to the name of your image file
  - "smoothing_iter" to the desired smoothing factor
  - "max_iter" to the desired number of iterations until termination
  - "K" to the desired number of clusters
- note: default settings in the notebook will reproduce paper results
- Run the notebook

### Author
- Matthew H. Goodman

