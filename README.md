** Face Recognition using Deep Learning** <br />
**Procedure:** <br />
**Data preparation** <br />
1. First collected 10 images of 22 each person. <br />
2. Rename the images with their roll number.  <br />
3. Perform the augmentation to increase the data size for deep learning training. <br />
4. Perpare CSV file that contains name of the images as compatible with Siamese Network.  <br />

**Approach:**
1. Get the encoding of image using **EfficientNet** model. <br />
2. Then use the euclidean distance to measure the similarity between two images.<br/>
3. Use triplet loss to get the match pair. <br/>

**Output:**<br/>
1. After the traning, we got the accuracy on the validation data as 92 percent.<br/>
2. Visual output:**<br />
![result2](https://user-images.githubusercontent.com/60688738/227464116-9458afc9-c206-4d6f-8ec5-48ac6f3a344c.png)   <br/>


**Face recognition using Landmark Estimation Algorithm:**<br/>

1. Find face in image.<br/>
2. Analyze facial features.<br/>
3. Compare against known faces.<br/>
4. Make a prediction.<br/>

**Output:** <br/>
![result4](https://user-images.githubusercontent.com/60688738/227464945-a15401ab-6589-4870-a005-e33fd6d43313.png)< br/>


**Folder Description:**<br/>
1. **Image** contains the images that is used to train the **Siamese Network**. <br/>
2. **Cv-project** folder contains the images that is used to learn using **Face Landmark Method**.<br/>
3. **Attendance.csv** file contains the name of student that come accross the camera while trial of the project and time also.<br/>
4. **Deeplearning.ipynb** contains the code for the Siamese network approach.<br/>
5. **Land_mark_approach.py** contains the code for the Landmark Estimation approach.<br/>
6. **augmentation.ipynb** contains code for augmentation of images.<br/>
7. **csv.ipynb** file contains the code to make the csv file for the Siamese network.<br/>
8. **face.csv** file is csv file that contains the data for the Siamese network.<br/>
9. **rename.ipynb** contains the code that is used for renaming all the images.<br/>
10. **utils.py** is used to show the neighbour images, using the Siamese Network.<br/>


