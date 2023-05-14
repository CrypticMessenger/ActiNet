# Human-Activity-Recognition-using-DL

Human Activity Recognition (HAR) is a field of study that aims to identify and classify human movements or actions based on sensor data. HAR has many applications in domains such as health care, sports, entertainment, and smart homes. One of the familiar sources of sensor data for HAR is smartphones, which have built-in inertial sensors such as accelerometers, gyroscopes, and linear accelerometers.
These sensors can capture the 3-axial linear acceleration and angular velocity of the smartphone at a fixed sampling rate. In the paper, authors have used a “sensor data collector” android application to collect data and create their own dataset, namely “H Activity.” The proposed model works exceptionally well on H-Activity, i.e., with 99.93% accuracy. Authors continue to benchmark the proposed model for other publicly available datasets like MHEALTH (98.76%) and UCI-HAR(93.11%).
My goal is to replicate the results for the MHealth dataset, which is publicly available since H-Activity is not accessible to the public. The MHealth dataset consists of data from 2 sensors namely attached to the left ankle and right-lower arm. Both sensors record triaxial linear acceleration and gyro. MHealth also consists of more categories than H-Activity for classification (12 compared to 4).
Through various experimentations, I was able to achieve exceptional accuracy of 99.69% for the MHealth dataset for 12-class classification.

## Dataset

dataset can be downloaded from [here](https://archive.ics.uci.edu/ml/datasets/MHEALTH+Dataset) or from [kaggle](https://www.kaggle.com/datasets/gaurav2022/mobile-health)

## Directory Structure

```
.
├── HAR_based_on_LSTM_architecture.pdf : Original Research paper
├── Model_architecture.png : Implemented model architecture
├── ProjectReport.pdf : Project Report
├── README.md : Readme file
├── Results : Results of the model
│   ├── ConfusionMatrix.png
│   └── FittingGraphs.png
└── Trained_Models : Trained models
    ├── 99.69.h5 : trained model with 99.69% accuracy
    └── 99.69.tflite : trained model with 99.69% accuracy in tflite format
```
