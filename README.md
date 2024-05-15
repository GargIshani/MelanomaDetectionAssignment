# Project Name
> In cancer, there are over 200 different forms. Out of 200, melanoma is the deadliest form of skin cancer. The diagnostic procedure for melanoma starts with clinical screening, followed by dermoscopic analysis and histopathological examination. Melanoma skin cancer is highly curable if it gets identified at the early stages. The first step of Melanoma skin cancer diagnosis is to conduct a visual examination of the skin's affected area. Dermatologists take the dermatoscopic images of the skin lesions by the high-speed camera, which have an accuracy of 65-80% in the melanoma diagnosis without any additional technical support. With further visual examination by cancer treatment specialists and dermatoscopic images, the overall prediction rate of melanoma diagnosis raised to 75-84% accuracy. The project aims to build an automated classification system based on image processing techniques to classify skin cancer using skin lesions images.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
  Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the background of your project?
 In the skin biopsy, the dermatologist takes some part of the skin lesion and examines it under the microscope. The current process takes almost a week or more, starting from getting a dermatologist appointment to getting a biopsy report.
 The aims to shorten the current gap to just a couple of days by providing the predictive model.
 The approach uses Convolutional Neural Network (CNN) to classify nine types of skin cancer from outlier lesions images. This reduction of a gap has the opportunity to impact millions of people positively.

- What is the business probem that your project is trying to solve?
  To build a CNN based model which can accurately detect melanoma.

- What is the dataset that is being used?
  The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Training and Validation Accuracy (Left Plot):

The training accuracy quickly rises and then plateaus at around 0.98, indicating that the model is learning the training data very well.
The validation accuracy also improves and stabilizes around 0.85, showing good generalization to unseen data with some fluctuations.
Training and Validation Loss (Right Plot):

The training loss decreases steadily and reaches very low values, indicating that the model fits the training data well.
The validation loss decreases initially but then fluctuates and shows some increase towards the end.
Conclusion:
Improvement in Overfitting:

The model shows reduced overfitting compared to previous iterations. The validation accuracy is close to the training accuracy, and the validation loss, despite some fluctuations, does not diverge significantly from the training loss.
Class Rebalancing Impact:

Class rebalancing appears to have helped the model generalize better. The validation accuracy improvement and the reduction in the validation loss fluctuations indicate that the model is now more robust and performs better across different classes.
Overall, the results show a significant improvement, indicating that the strategies employed have been effective in enhancing the model's performance.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@GargIshani] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->