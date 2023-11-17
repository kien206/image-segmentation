# image-segmentation

## Report

### Transformations techniques

- I applied ColorJitter, RandomHorizontalFlip, RandomVerticalFlip and Gaussian Blur to transform the data

- Add 40% of the augmented data to the original data to be my train data

### Model changes

- I used a pretrained Unet++ model with imagenet weights

- Modified epoch = 30, learning_rate = 1e-04
