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

![flowchart](https://user-images.githubusercontent.com/91828519/162007032-8cb3719b-1c06-46a3-8b52-311e10ec4196.png)
propose block diagram 

# Results
Contrast adjustment to highlight tumor tissue

<img src="https://user-images.githubusercontent.com/91828519/162019373-03b4b0f8-f924-4332-b948-8b3fac5b17aa.png" width="700" alt="contrast-adjustment">
<figcaption align = "center"><b>Fig2. Adjust the contrast in different ranges</b></figcaption>


According to the results of the desired windowing on the images, we see the highlighting of tumor areas and image improvement for better extraction of these areas. As a result, selecting the window in the appropriate range can give a better quality to the output image to perform the desired operations in the next steps.

 <img src="https://user-images.githubusercontent.com/91828519/162024718-c2385b7f-284a-438e-8705-0b207e17b091.png" width="599" alt="result-of-contrast">
<figcaption align = "center"><b>Fig3. Adjust the contrast in different ranges and its results: a) original image b) Contrast adjustment in the range [0-100] c) in the range [50-150] d)in the range [100-200]</b></figcaption>

Morphological operations are performed after Region-based segmentation to improve the tumor area and make its border more accurate.

<img width="698" alt="fig4-6" src="https://user-images.githubusercontent.com/91828519/162045441-c44b8a3b-1dd3-4963-8be4-7c404096fca3.png">
<figcaption align = "center"><b>Fig4.Image segmentation results: a)original image b)Binary image c)Region-based segmentation d)The final area of the tumor in the image</b></figcaption>


# Follow the following steps to run the program:
>For the first time :
>1. Upload your dataset
>2. Training database
-----------
1. Run BrainMain.m
2. Select images from dataset
3. Observe segmentation and classification results

