This project implements 5 computer vision models for mask detection in images and videos.  Implemented methods

The computer vision models: 
- Resnet-50
- Mobilenet V2
- Custom convoluational neural network (CNN)
- Histogram of features (HOG) + support vector machine (SVM)
- Scale-Invariant Feature Transform (SIFT) + support vector machine (SVM).

For all the models, the train images and labels were split into 80% training set and 20% validation set.

The models are too large to upload to GitHub, but the training, validation, and testing code can be found in this repository. The code for the HOG + SVM and SIFT + SVM models can be found in the file `SVMs.ipynb`. The code for the Resnet-50 and Mobilenet V2 models can be found in the `PretrainedCNNs.ipynb` file. The custom CNN code can be found in the file `KerasCustomCNN.ipynb`.
