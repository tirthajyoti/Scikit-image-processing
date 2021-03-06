### Please feel free to [connect with me here on LinkedIn](https://www.linkedin.com/in/tirthajyoti-sarkar-2127aa7/) if you are interested in data science and machine learning.

---

# Image processing examples with Numpy, Scipy, and Scikit-image

### Requirements

* **Python 3.4+**
* **NumPy (`$ pip install numpy`)**
* **SciPy (`$ pip install scipy`)**
* **MatplotLib (`$ pip install matplotlib`)**
* **Scikit-image (`$ pip install scikit-image`)**

---

### Testing after install

Open a Jupyter notebook and execute the following code,
```
import numpy as np
import matplotlib.pyplot as plt
from skimage import data, io, filters

image = data.coins()  # or any NumPy array!
edges = filters.sobel(image)
io.imshow(edges)
```

You should see the following output. If you see this, you are all set to go!

![sobel_coins](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/sobel_coins.PNG)

---

### Simple NumPy array based operations
* [Demo of NumPy based image manipulation](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Using_Numpy_image_manipulation.ipynb)<br>
<img src="https://raw.githubusercontent.com/tirthajyoti/Scikit-image-processing/master/images/Numpy_image_manipulation.png" width="700" height="200" />

* [Block view function and pooling/sampling](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Block_view_mean_max_median_sampling.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/block_view_pooling_sampling.PNG" width="350" height="350" />

* [Zooming (interpolation) based on SciPy](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Scipy_zooming.ipynb)

---

### Exposure and color channel manipulations
* [RGB to gray conversion](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/RGB2Gray.ipynb)<br>
<img src="https://raw.githubusercontent.com/tirthajyoti/Scikit-image-processing/master/images/rgb2gray.PNG" width="360" height="200" />

* [RGB to HSV (Hue-Saturation-Value) conversion](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/RGB_to_HSV.ipynb)<br>
<img src="https://raw.githubusercontent.com/tirthajyoti/Scikit-image-processing/master/images/rgb2hsv.PNG" width="640" height="180" />

* [Adapting gray-scale filters to RGB images using special decorator](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Adapt_RGB_decorator.ipynb)

* [Adjusting contrast by filtering regional maxima](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Filtering_regional_maxima.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/filtering_regional_maxima.PNG" width="600" height="170" />

* [Local Histogram equalization](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Local_Histogram_Equalization.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/Local_histogram_equalization.PNG" width="400" height="280" />

* [Gamma and log contrast](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Gamma_log_contrast_adjustment.ipynb)

* [Tinting grayscale images](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Tint_Grayscale.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/tint_grayscale.PNG" width="400" height="280" />

---

### Edges, lines, and contours

* [Finding contours](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Finding_contours.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/finding_contours.png" width="600" height="240" />

* [Convex Hull of an image](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Convex_Hull.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/convex_hull.PNG" width="600" height="240" />

* [Skeletonize 2-D and 3-D images](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Skeletonize.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/skeletonize.png" width="360" height="280" />

* [Marching cubes](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Marching_cubes.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/marching_cubes.PNG" width="400" height="400" />

* [Edge operators](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Edge_operators.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/edge_operators.png" width="600" height="400" />

---

### Geometrical transformations and registration

* [Swirl](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Swirl.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/Swirl.png" width="400" height="200" />

* [Interpolation - edge modes](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Interpolation%20-%20Edge%20modes.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/interpolation_edge_mode.PNG" width="400" height="200" />

* [Rescale, resize, downscale](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Rescale_resize_downscale.ipynb)

* [Histogram matching](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Histogram_matching.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/histogram_matching.PNG" width="400" height="130" />

* [Structural similarity index](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Structural_similarity_index.ipynb)

### Filtering and restoration

[Hysteresis thresholding](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Hysteresis_thresholding.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/Hysteresis_thresholding.PNG" width="400" height="400" />

[Image deconvolution](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Image_deconvolution.ipynb)

[Unsharp mask](https://github.com/tirthajyoti/Scikit-image-processing/blob/master/Unsharp_mask.ipynb)<br>
<img src="https://github.com/tirthajyoti/Scikit-image-processing/blob/master/images/unsharp_mask.PNG" width="400" height="400" />
