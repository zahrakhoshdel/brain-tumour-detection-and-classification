# Brain Tumour Detection and Classification
Automatically classifies brain tumor images into malignant and benign using Matlab
> The proposed algorithm tries to detect the tumor area more accurately.

# Abstract
The proposed system scans the Magnetic Resonance images of brain. The scanning is followed by preprocessing which enhances the input image and applies filter to it. After enhancement, the image undergoes segmentation and feature extractions. Based on the feature extraction the system identifies whether the tumor is cancerous or non - cancerous (benign).

Demo Video

https://user-images.githubusercontent.com/91828519/162007703-dddc2c75-ebb1-46f0-8e3f-af41ec2572aa.mp4



# Flow of the project
1. Image Input
2. Processing of Image: Usage of Noise removal and Contrast Adjustment
3. Image Segmentation
4. Feature Extraction
5. Classification of the Tumor

<p align = "center">
<img src = "https://user-images.githubusercontent.com/91828519/162007032-8cb3719b-1c06-46a3-8b52-311e10ec4196.png">
</p>
<p align = "center">
Fig.1 - propose block diagram 
</p>


# Results
Contrast adjustment to highlight tumor tissue

<p align = "center">
<img src="https://user-images.githubusercontent.com/91828519/162019373-03b4b0f8-f924-4332-b948-8b3fac5b17aa.png" width="700" alt="contrast-adjustment">
</p>
<p align = "center">
Fig2. Adjust the contrast in different ranges 
</p>


According to the results of the desired windowing on the images, we see the highlighting of tumor areas and image improvement for better extraction of these areas. As a result, selecting the window in the appropriate range can give a better quality to the output image to perform the desired operations in the next steps.

<p align="center">
  <img alt="result-of-contrast" src="https://user-images.githubusercontent.com/91828519/162472864-e65faece-7cb5-4350-b28c-652750b7d4e7.png" width="600">
  <br>
    <em>Fig3. Adjust the contrast in different ranges and its results: a) original image b) Contrast adjustment in the range [0-100] c) in the range [50-150] d)in the range [100-200]</em>
</p>


Morphological operations are performed after Region-based segmentation to improve the tumor area and make its border more accurate.

<p align = "center">
<img src="https://user-images.githubusercontent.com/91828519/162473913-437c353f-20a2-4371-9996-ac8609f2d395.png" width="700" alt="image_segmentation">
</p>
<p align = "center">
Fig4.Image segmentation results: a)original image b)Binary image c)Region-based segmentation d)The final area of the tumor in the image
</p>


# Follow the following steps to run the program:
>For the first time :
>a. Upload your dataset
>b. Training database

1. Run BrainMain.m
2. Select images from dataset
3. Observe segmentation and classification results

