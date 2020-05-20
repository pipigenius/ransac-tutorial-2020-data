## RANSAC 2020 tutorial starter pack (in progress)

# Data for epipolar geometry training and validation

Training and validation data you can download from http://cmp.felk.cvut.cz/~mishkdmy/CVPR-RANSAC-Tutorial-2020/RANSAC-Tutorial-Data-EF.tar

12 scenes, 100k image pairs each, so 1.2M cases for training, 86 Gb.
The data comes from train and validation set of the [CVPR IMW 2020 PhotoTourism challenge](https://vision.uvic.ca/image-matching-challenge/data/)


Jupyter notebook, showing the format of the data and toy evaluation example is [here](parse_EF_data.ipynb).



Your methods can use as an input:

x, y, matching score for fundamental matrix case 

and x,y, matching score, calibration matrices K1, K2 for essential matrix case.

The code for running OpenCV RANSACs evaluation on the validation set is coming soon.

The test data (only input) is coming soon.

[**PyTorch data loader**](hdf5reader.py)


# Data for training and validation of PnP methods

Coming soon (expect on  May 20-21)


# Data for hyperparameter tuning for homography. No training data

Coming soon (expect on  May 20-22)


# Other cases (3d point cloud regstration, etc)

TBA if any.


