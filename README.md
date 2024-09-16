# Malenoma Detection Prediction
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a CNN based model which can accurately detect melanoma
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
- A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Dataset: https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=sharing

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- 1) Simple Sequential CNN Model resulted very very low accuracy and high loss function model
- 2) Second MOdel with dropouts and Data augumentation improved accuracy and decreasing loss function but has evidence of overfitting
- 3) Third Model including CLass Imbalance Logic improved accuract but still has evidence of overfitting
- 4) Prediction on Test Data based on Third Model shows evidence of Overfitting with accuarcy of 47%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- tensorflow - version 2.17.0
- matplotlib - version 3.9.2
- numpy - version 1.26.4
- pandas - version 2.2.2
- Augmentor - version 0.2.12


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- Upgrad MS (ML) Project Assignment
- Tensor Flow - Data Augumentation, Class Imbalance KNowledge Repository
- Used Google Collab GPU for Execution


## Contact
Created by [@ganesh-hariraj] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->