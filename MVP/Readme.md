# Instagram pages according to interest 
## Overview
In this project we extract the dataset from [Kaggel](https://www.kaggle.com/bahramjannesarr/instagram-page-screen-shots-in-5-category) which is a dataset containing over 3770 screenshots images into 5 categories to build a deep neural network model that uses screenshots of several posts on an Instagram page as one image to identify the interest of that page.
## Workflow
### EDA:
- Sample of Dataset after uploading it.

<p align="" width="25%">
<img src="https://user-images.githubusercontent.com/93087607/148681445-abf2776d-fd76-4a03-82e2-7f578f87f2ec.png" />
</p>

- Distribution of images in each class.

<p align="" width="">
<img src="https://user-images.githubusercontent.com/93087607/148681451-4af8791d-1e5c-4802-a926-19c9c516afb1.png" />
</p>

### Modeling:
- Baseline: Logistic Regression

<p align="" width="10%">
<img src="https://user-images.githubusercontent.com/93087607/148682133-d9366d5d-e326-4a14-bf4f-2a93f69fc78e.png" />
</p>

- Simple Neural Network : with 6 hidden layers using 'tanh' and 'softmax' activation functions.

<p align="" width="10%">
<img src="https://user-images.githubusercontent.com/93087607/148682825-88b34fbc-5ee6-490c-82d3-0b3058ffada6.png" />
</p>

#### As is shown the score performance of Simple Neural Network model it did not get better from the logistic baseline, So i will gonna try build a complex neural network model to increase the score.

## Future Work
- Convolutional Neural Network (CNN)
- Transfer Learning
- test by the best Model.


