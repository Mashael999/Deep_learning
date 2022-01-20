# Instagram profile classification


## Design:
The goal of this project is to build a deep neural network model that uses screenshots of several posts on an Instagram page as one image to identify the interest of that page.

## Data:
The used dataset downloaded from [Kaggle](https://www.kaggle.com/bahramjannesarr/instagram-page-screen-shots-in-5-category) which contains 3770 images into 5 folders labeled as to which class they belong to.

 
## Algorithms

#### Exploratory And Processing Dataset
- Reading the data
- Resize images to height and width into 200 and 150
- Normalization (divide by 255)
- Data augmentation
  - Flip ‘horizontal ‘and ‘vertical’
  - Rotation (90)
  - Shifting 
- Split Dataset 
  - Training=  80%, 3053 images
  - Validation= 10%, 340 images
  - test= 10%, 377 images


#### Natural Langauge Processing
Several models with multiple experiment were tried and played with to get the best model that goes hand in hand with the dataset. After performing simple train and validation on the  models one was chosen for further investigation. Models trained was:
The classification algorithm that has been used in this project:

- Logistic Regression
- Natural networks
- CNN
- Transfer Learning
  -  VGG16
  -  VGG19
  -  MobileNet
  -  EfficientNetB2
 
Best Algorithm that made gave the best results is MobileNet with one Conve2D layers and 3 Dense layers with Droupout 0.25.




## Tools:
- Numpy 
- Pandas 
- Matplotlib 
- keras  
- Sklearn 
