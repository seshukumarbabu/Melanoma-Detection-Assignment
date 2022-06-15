# Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer 
that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution 
that can evaluate images and alert dermatologists about the presence of melanoma has the potential 
to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer 
that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution 
that can evaluate images and alert dermatologists about the presence of melanoma has the potential 
to reduce a lot of manual effort needed in diagnosis.
- What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases, 
which were formed from the International Skin Imaging Collaboration (ISIC). 
All images were sorted according to the classification taken with ISIC, and all subsets 
were divided into the same number of images, with the exception of melanomas and moles, 
whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 with Model1 - Model is Overfitting as Training Accuracy is 0.77 and Validation Accuracy is 0.44
- Conclusion 2 with Model2 - Both the Training and Validation Accuracies are 0.51 and 0.48, which shows now the model is Underfitting.
- Conclusion 3 with Model3 - Class Rebalance definitely helped in improving the model performance. 
							 But I still see that there is a larger gap between Training Accuracy (0.95) and 
							 Validation Accuracy (0.77). Which means that we can still improve the model.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.x
- tensorflow and Keras
- Pandas
- Numpy
- Augmentor

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@seshukumarbabu] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->