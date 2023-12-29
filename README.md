Description
Objective

The primary objective is to develop a deep-learning model that can classify plant diseases based on images. Participants will use the provided training dataset, which consists of images resized to a maximum dimension of 600 pixels while maintaining the aspect ratio. The challenge is to use these images to train models that can accurately classify plant diseases in the test set.
Data Description

Source: Derived from the Plant Pathology 2021 - FGVC8 Kaggle competition (https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8).
Training Set: Publicly available images, resized with the largest dimension capped at 600 pixels. The dataset includes various classes of plant diseases.
Test Set: A separate set of images, similarly processed, to be used for evaluating the models.
Acknowledgement

Source: https://www.kaggle.com/competitions/plant-pathology-2021-fgvc8

For the original Kaggle Competition, details and background information on the dataset and Kaggle competition ‘Plant Pathology 2020 Challenge’ were published as a peer-reviewed research article.

Evaluation

The evaluation metric for this competition is Mean F1-Score.
Submission File

Submission files should contain two columns: image and labels. labels should be a space-delimited list.

The file should contain a header and have the following format:

image, labels
test_iamge_1.jpg, healthy
test_iamge_2.jpg, healthy
test_iamge_3.jpg, healthy
, etc.
