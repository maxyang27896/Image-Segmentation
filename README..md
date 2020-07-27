# Image Segmentation Project
A tensorflow auto encoder model that has been trained on two sets of dataset to achieve the image segmentation tasks. The model used was a unet model where the downsampling layers are part of a pretrained model previously trained on the ImageNet dataset and is frozen during training on our dataset. Additional upsampling layers were added to be trained to produce the desired segmentated image. 

## Considition Segmentation
The model input is drone images of rural areas and the output image is to dstinguish between road, water, building or none of the above. ![Considition](./img/Predictions3.png)

## Forest Segmentation 
