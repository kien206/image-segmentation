# image-segmentation

## Report

### Transformations techniques

- I applied ColorJitter, RandomHorizontalFlip, RandomVerticalFlip and Gaussian Blur to transform the data

- Add 40% of the augmented data to the original data to be my train data

### Model changes

- I used a pretrained Unet++ model with imagenet weights

- Modified epoch = 30, learning_rate = 1e-04

### How to run infer.py

- Clone the repository

```sh
git clone https://github.com/kien206/image-segmentation
```

- Go to **https://drive.google.com/drive/folders/19NbndnpabvaADIrTiniZo-XEyfIiYySQ** and download **unet_model.pth** file

- Move the **unet_model.pth** to the cloned repo folder
  
```sh
mv unet_model.pth # cloned folder path
```

- Cd to the cloned repository folder
```sh
cd # cloned folder path
```

- Run infer.py
```sh
python infer.py
```
