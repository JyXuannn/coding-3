# coding-3

## Video link:https://www.youtube.com/watch?v=I44dSJ1mNqE

## Dataset: https://www.kaggle.com/datasets/sirakr/houses-dataset

## Concept: 

With the development of the times, new styles of architecture are emerging all over the world, and some of the buildings combine different architectural styles to explore new possibilities.

Therefore, I searched for a database on architecture and I wanted to train architectural models from the DCGAN method in order to explore more architectural possibilities.

## Description:  

This is a benchmark dataset for houses prices that contains both visual and textual information. Each house is represened by four images for bedroom, bathroom, kitchen and a frontal image of the house. This is the first dataset that contains images to be used for houses prices estimation. The dataset folder contains 2140 images, 4 images for each house. Also, it contains a text file that contains the textual metadata of the dataset. Each row in the file respesents the number of house in order. The numbers represent number of bedrooms, number of bathrooms, area of the house, zipcode and the price. 

After downloading the dataset for the first time I chose the frontal part (about 500 photos, which I trained 10,000 times to ensure the final result).

![Image text](https://github.com/JyXuannn/coding-3/blob/main/img-folder/generated_images_epoch_10000.png)

However, I thought I could try to select more architectural styles to train, so I put in all the images from the dataset and started training (about 2000 images). So I only trained 2000 times, but I think the results are better than before.

![Image text](https://github.com/JyXuannn/coding-3/blob/main/img-folder2/generated_images_epoch_2670.png)

There were too many images in the dataset so it was impossible to upload them. Just download the dataset and put it in the frontal folder in the data file and it will work. (The link to the dataset has been placed above)

The reference code is mainly week 5 content(DCGAN): https://git.arts.ac.uk/rfiebrink/ExploringMachineIntelligence_Spring2023/blob/main/week5/dcgan.ipynb and the previous weeks.

I have also saved an image of the dataset here (in Dropbox)： https://www.dropbox.com/scl/fo/s3xs8k4zqtn1lfk4r0adb/h?dl=0&rlkey=6e94nzedk49j9vqn9plxai3gd

There are also images of the training process (one saved for every 10 epoch of training)： https://www.dropbox.com/scl/fo/8fhrpuv4lr24r2aqt42tt/h?dl=0&rlkey=d0rxw6jy9io2exxc9pd3dl5t2
