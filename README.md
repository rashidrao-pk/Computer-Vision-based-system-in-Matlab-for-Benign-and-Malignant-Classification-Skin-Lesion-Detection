# Computer-Vision-based-system-in-Matlab-for-Benign-and-Malignant-Classification-Skin-Lesion-Detection

### Task :
<br>
![image](https://user-images.githubusercontent.com/25412736/177776544-f86e24c1-e627-4288-8ff5-c9fcf3917b42.png)
<br>

Required Method to be Implemented:
![WhatsApp Image 2022-02-20 at 6 33 47 AM](https://user-images.githubusercontent.com/25412736/177776710-93f71389-9541-4e63-a07d-c212eb6c940f.jpeg)


## Phase 1: 	  File Name: Skin_Lesion_Segmentation.m
		Step 1: Set Segmentation Accuracy Limit (i.e 80% now).
		Step 2: Run The code, it will automatically segment all the images from dataset path and will 			save all images to either benign or malignant by using labels       provided in GroundTruth.			txt file
		Step 3:	Command window will show the current progress of the segmentation algorithm.
		Step 4:	Figures and Subplot will show the visual performance of the segmentation algorithm.
		Step 5:	Finally, "000_Segmented.txt" file will be created having details about segmentation 			success cases.
		Step 6:	"000_FailCases.txt" file will be created having details for fail cases.

## Phase 2:    File Name: 	Skin_Lesion_Classification_Final.m
		Step1: 	Set the Dataset portion Slpitting %
		Step2:	Set Feature Vector Reduction Ratio
		Step3:	Run the Code
		Step4:	After Fusion and Feature Vector Finalization, results can be evaluated using 					Classification Learner app from Computer Vision Tool Box.
		Step 5:	Save Classfier training File

## Phase3:
	FileName: Skin_Lesion_Classification_Final.m
		Step 1 : Load the trained classifier from directory
		Step 2 : Calculate the Sensitiy and Specificity using Confusion Matrix



