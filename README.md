# Semantic-Segmentation-of-Satellite-Imagery

Semantic segmentation, which involves classifying each pixel in an image into distinct object categories, is a crucial step in extracting meaningful information from aerial images. Aerial imagery is a challenging domain for semantic segmentation due to its high resolution and large size. This approach addresses this challenge by using patchify, which is a technique that divides an image into smaller patches before processing it. This is followed by training and deploying U-Net, a popular deep learning architecture to predict the semantic labels of each pixel in the patches. The publicly available dataset of aerial imagery of Dubai captured by MBRSC satellites is used, containing 6 classes colour coded with different hex codes. The results show that this method is able to extract valuable insights and facilitate informed decision-making by predicting the segmentation mask of the aerial images with a validation accuracy of 86.11%.

Methodology:
![image](https://github.com/user-attachments/assets/f0b0c244-474e-4492-a6d5-2d772f6b7a33)

Results:
![image](https://github.com/user-attachments/assets/4b97300d-8940-4bac-abff-28a078dd3c99)

Accurcy and loss curves:
![image](https://github.com/user-attachments/assets/a9849b64-f3cb-427d-8016-fa0d94ab445b)
![image](https://github.com/user-attachments/assets/036c8dd8-13ef-4f96-a99f-a0db4e23ef9e)

