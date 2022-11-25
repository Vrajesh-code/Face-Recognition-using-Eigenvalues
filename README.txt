

Dataset used --> olivetti_faces
90% images (360 images) were used for training and rest(40 images) were used for testing purpose.
 
The report and the python files contain the detailed analysis of the implementation. Kindly refer them for wholistic understanding of the implementation.

Functions: What they do
pca: Will return the eigenfaces and mean vector of all vector faces using principle component analysis(PCA) algorithm
face_detection: Will return Face detected if the input image is detected in dataset and will return unknown face if the input image is not detected in dataset.
recognize: Will return the indexes of the images in the dataset that match with the input image. Will also return the index of the best matched image.
accuracy: Will return the accuracy of the image detection. If the label of the best matched image matches the actual label than it the detection will be considered correct.

Kindly note that the role of different parameters is commented in the ipynb file and is also disscused in the report.







