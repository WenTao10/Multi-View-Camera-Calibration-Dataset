# Multi-View-Camera-Calibration-Dataset (MVCCD)
The multi-view camera calibration dataset aims to train a deep network to estimate vanishing points and external camera parameters. In this dataset, each image has a unique camera rotation angle, and the label file stores the name, vanishing point, and camera pose of each image.

- This dataset contains 17 typical expressway scenes and is divided into nine straight road scenes and eight curved road scenes according to the expressway appearance.
- There are 32,712 images in the dataset. The training set accounts for 67%, the validation set accounts for 17%, and the test set accounts for 16%.
- These images are available in RGB format and 1920x1080 resolution.
- The pitch angle of the camera varies in the range of [0°, 19.8°], while the yaw angle ranges from [−29.3°, 29°].
- The average camera height is about 12m.

# Dataset
This dataset is published in [BaiYun](). Its structure is illustrated in the following figure.
![](https://github.com/WenTao10/calibration-images/blob/main/dataset.png)
## Image Demo
### Sraight Road
![](https://github.com/WenTao10/calibration-images/blob/main/K407%2B890.jpg)
![](https://github.com/WenTao10/calibration-images/blob/main/K266%2B450.jpg)
### Curved Road
![](https://github.com/WenTao10/calibration-images/blob/main/009363_K347%2B595.jpg)
![](https://github.com/WenTao10/calibration-images/blob/main/009838_K385%2B690.jpg)

## Label Format
In each sub-dataset (training, validation, and test), there is a label file which is named "vpt_and_camera_pose.txt." This label file contains the image name, vanishing point, pitch angle, yaw angle, camera focal length, and camera height.
The following figure illustrates the demo of the label file.
![](https://github.com/WenTao10/calibration-images/blob/main/label.PNG)
