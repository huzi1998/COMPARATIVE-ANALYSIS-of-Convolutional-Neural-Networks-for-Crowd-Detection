# COMPARATIVE-ANALYSIS-of-Convolutional-Neural-Networks-for-Crowd-Detection
This research delves into the applications CNNs in crowd counting and tracking, a domain critical for optimizing operations, ensuring safety, and making informed decisions in diverse industries. Utilizing Convolutional Neural Networks (CNNs), this study assesses four prominent models, namely YOLOv5, YOLOv8, RetinaNET, and RTMDet, against two datasets encompassing varied crowd densities.
Our findings highlight YOLOv8 as the optimal choice due to its exceptional accuracy, precision, and F1-score, making it ideal for crowd counting, detection, and tracking. The integration of BYTE Tracker further enhances YOLOv8's performance, ensuring precise individual tracking within crowded scenes.

## Architecture
<img width="218" alt="image" src="https://github.com/huzi1998/COMPARATIVE-ANALYSIS-of-Convolutional-Neural-Networks-for-Crowd-Detection/assets/49037693/1d289fb1-661b-4ff1-bf5d-eb4d2df35b1a">

## Dataset 

<img width="204" alt="image" src="https://github.com/huzi1998/COMPARATIVE-ANALYSIS-of-Convolutional-Neural-Networks-for-Crowd-Detection/assets/49037693/4511bab8-ba8c-4cd9-b8ac-aa9744c39492">


<img width="190" alt="image" src="https://github.com/huzi1998/COMPARATIVE-ANALYSIS-of-Convolutional-Neural-Networks-for-Crowd-Detection/assets/49037693/3119d4b6-3259-4667-b6d0-80f9e4396a7f">

The datasets were collected from a data source which was developed by Karthika, N. J [25] in year 2020 and is available at https://www.kaggle.com/datasets/karthika95/pedestrian- detection while the other dataset set was collected from open images v6 which is available at https://storage.googleapis.com/openimages/web/visualizer/index.html?type=segmentation &set=valtest&c=%2Fm%2F01g317 and then both of the datasets were merged together.

## Results and Evaluation

![6BB5F23F-6EB0-4EDF-9A8F-8A8F6AB46C11_1_201_a](https://github.com/huzi1998/COMPARATIVE-ANALYSIS-of-Convolutional-Neural-Networks-for-Crowd-Detection/assets/49037693/7a4cf9ba-948f-44ac-acb7-a5a572dd7f42)

1.	Yolov8: Yolov8 appears to have one of the highest accuracies (map_50) among the models on both Dataset 1 and Dataset 2. It may be a suitable choice if accuracy is your primary concern. Since crowd detection and counting requires high accuracy to we should use YOLOv8. However, you should also consider its training time and model complexity.
2.	Yolov5: Yolov5 achieved a higher F1-score on Dataset 2 compared to Yolov8, indicating better object localization for crowd detection and a balance between precision and recall. It may be a good choice if you value localization accuracy and a balanced F1-score in your Crowd Detection Applications.
3.	RetinaNET: RetinaNET achieved relatively high accuracy and recall on both datasets. It is known for its ability to handle Crowds of various sizes effectively. If robustness across different object sizes is essential for your application, RetinaNET might be a strong candidate.
4.	RTMDet: RTMDet also performed well, particularly in terms of precision on Dataset 2. If precision is crucial for your application, RTMDet could be a suitable choice for Crowd Detection.


<img width="456" alt="image" src="https://github.com/huzi1998/COMPARATIVE-ANALYSIS-of-Convolutional-Neural-Networks-for-Crowd-Detection/assets/49037693/2707967f-ec09-4c1f-ad28-2dabe7101c4a">





  
