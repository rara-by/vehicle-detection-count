# vehicle-detection
This is a deep learning/computer vision project on vehicle detection, classification and counting on an image dataset.

YOLOv5 (small) model has been used for object detection and classification, which is based on https://github.com/ultralytics/yolov5. 

The dataset can be found here - https://datasetsearch.research.google.com/search?query=object%20detection&docid=L2cvMTFrZHFtdzljcg%3D%3D
<br> Number of train set - 439 images,
valid set - 125 images,
and test set - 63 images.
Total images in the dataset = 627<br>
This dataset contains images of Ambulances, Buses, Trucks, Cars and Motorcycles.

The **main.ipynb** file is the notebook containing necessary codes, descriptions and visualizations. It is a Colab notebook. <br>
The **Dataset** folder contains the dataset sans duplicates generated from roboflow. <br>
The **Train/vehicle5** folder contains generated weights, plots (F1 curve, precision and recall curves, confusion matrix etc.) from training the train set using the YOLOv5s architecture. <br>
The **Results** folder contains the predicted images in the *detect* subfolder, *count.csv* (contains count of different classes in a single image), *result.csv* (DataFrame of predicted labels and bounding boxes).

![image](https://user-images.githubusercontent.com/63100531/125672663-f834d701-4c9d-44fe-9041-01b238ab2830.png)
*Figure: Training metrics*

![image](https://user-images.githubusercontent.com/63100531/125672868-4e630d9a-3a58-4b41-afe8-45b5a0583a3f.png) <br>
*Figure: Detection*




