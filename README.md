# da-Vinci-Xi-Live-tumor-detection
This repository contains the dataset and code used for the paper "Enabling da Vinci Xi Robot with Live Tumor detection via Explainable Deep Learning"

**Image dataset folder copy(classification)**

This is the main folder that contatins all the images. In here, is a folder called "Partial robotic nephrectomy" which contains all the images with cancerous tissue. There is another folder called "Kidney" which contains all the images with non-cancerous tissue. The images were further cropped so that the robotic arms from the original images don't show up. The cancerous tissue images are in teh folder called "Partial robotic nephrectomy cropped photos" and the non-cancerous tissues are in the folder called "Kidney cropped photos". The fatty tissues are in "Fat cropped photos". 

If you want to look at where the tumors are in the original images refer to "Label draft.pptx".

In "Partial robotic nephrectomy cropped photos" there are 44 images. 30 images were extracted into training set, 9 images were extracted into validation set, 5 images were extracted into test set. 
Since the images will be extracted from the cropped photos folders everything from the Image dataset folder copy (classification) will be copied into Thesis data(1st).

Now, Image augmentation was applied in the training set of Thesis data(1st) to make 1 image into 5 images. 

For teh 2nd dataset,looking Thesis data (1st) fatty tissue training data there were 21 images. 21 x 5 = 105. So, the first 21 images from the cancerous tissues, non cancerous tissue, fatty tissue were augemented to be 105 images in all cases. SO, there are 315 images for the training set in the 2nd dataset. 32 images for validation and 20 images for testing.

For the 3rd dataset, fatty tissue was not taken into account. From the 1st dataset there were 30 cancerous tissue and 40 non cancerous tissue for the training set. So, in order to keep the numbers equal, all the cancerous tissues were augmented but 30 out of 40 non cancerous tissues were augmented. That resulted in 150 training cancerous tissue and 150 training non cancerous tissue images.

