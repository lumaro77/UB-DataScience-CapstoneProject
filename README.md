# PostGraduated-DataScience-CapstoneProject
Lucas Martínez personal Capstone Project for the UB Data Science Postgraduated course 2021-2022. http://www.ub.edu/datascience/postgraduate/

Notebook with the developed tests is available on **Collab_Notebook/(/Collab_Notebook/)** folder. The notebook is configured to be run in [Collab](https://colab.research.google.com/). Persistence is ensured via the google-drive asociated with the Collab user.

## Quick user guide

### Available CNN models

3 models are available to perform train, re-train or a posterior evaluation.
- Set up ```mode01=True``` for a **self-CNN** model
- Set up ```mode11=True``` for a **ResNet based CNN** model 
- Set up ```mode11=True``` for a **DenseNet based CNN** model 

### Training and Evaluating modes
When training:
- **Retrain:** for a training from scrath set up ```retrain=False```, to resume a previous training set up ```retrain=True```
- **Epochs:** set up ```num_epochs```, to the desired number of epochs to train or retrain
When Evaluating:
- **Evaluation:** Set up ```evaluating=True``` to make an evaluation of a previous training.

## Report

Report will be available at: https://lumaro77.github.io/CapstoneProject-UBPostGraduated-DataScience/

Barcelona, June 2022.
