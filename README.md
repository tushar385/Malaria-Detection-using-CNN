# Malaria-Detection-using-CNN

System will read the image uploaded by the user, augment it and will use the saved custom model to detect whether the disease is present or not in the patient and thus display the result in a user-friendly language.

##### Below are the steps:-
- **Upload Image:**
The user can upload the medical test image through a workstation running on Windows OS. The image should be in jpeg, png or jpg format.
- **Read Image:**
The image will be scanned before augmentation takes place.
- **Transform Image:**
The scanned image is then transformed into a format that is needed by the saved custom model.
- **Evaluate image using saved model:**
After uploading the medical test image and output are predicted using the saved model.
- **Determine and Analyze the Output:**
The predicted output is then analyzed and converted to a user friendly language.
- **Display the Output:**
The analyzed result is then displayed to the user.

## Content Inside Dataset.zip

1. Train Folder  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Parasite  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Uninfected

2. Test Folder  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Parasite  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Uninfected


## Random Examples of Infected Sample

![](https://github.com/tushar385/Malaria-Detection-using-CNN/blob/master/Screenshot/Infected/C39P4thinF_original_IMG_20150622_105554_cell_11.png)
![](https://github.com/tushar385/Malaria-Detection-using-CNN/blob/master/Screenshot/Infected/C39P4thinF_original_IMG_20150622_105554_cell_13.png) 
![](https://github.com/tushar385/Malaria-Detection-using-CNN/blob/master/Screenshot/Infected/C39P4thinF_original_IMG_20150622_105554_cell_26.png)

## Random Examples of Uninfected Sample

![](https://github.com/tushar385/Malaria-Detection-using-CNN/blob/master/Screenshot/Uninfected/C3thin_original_IMG_20150608_162922_cell_191.png)
![](https://github.com/tushar385/Malaria-Detection-using-CNN/blob/master/Screenshot/Uninfected/C3thin_original_IMG_20150608_162922_cell_205.png)
![](https://github.com/tushar385/Malaria-Detection-using-CNN/blob/master/Screenshot/Uninfected/C3thin_original_IMG_20150608_162922_cell_211.png)

## Technology Used

1. Python
2. VGG19
3. ImageDataGenerator
4. Numpy
