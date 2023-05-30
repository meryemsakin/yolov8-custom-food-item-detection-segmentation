# yolov8-custom-segmentation

This repository contains a model based on YOLOv8 (You Only Look Once version 8). This model is designed to provide advanced object detection and segmentation capabilities. Specifically, this model has been trained to detect and segment food items such as oil, jam, tomatoes, pasta, rice, soda, and tomato sauce, found in a custom food dataset.

<td><img src="https://github.com/meryemsakin/yolov8-custom-segmentation/blob/main/r10.jpeg" width="500" height="500"></td>


YOLOv8 is an object detection system built on the principle of scanning objects only once. This makes it both fast and accurate, as it perceives the entire image not at once but by dividing it into multiple regions. This regional scanning strategy enables YOLOv8 to detect multiple objects simultaneously.

The model presents a range of applications for detection and segmentation of food items. For instance, it can be used to understand which products are most picked up by customers in a supermarket or to determine which ingredients are most used in a restaurant. It can also be employed to determine the quality and freshness of food items.

Leveraging the powerful deep learning algorithm and extensive capabilities of YOLOv8, this model can detect and segment a wide range of food items quickly and accurately. The aim of this model is to maximize accuracy, speed, and efficiency in food detection and segmentation.







## Metrics
![Accuracy](https://github.com/meryemsakin/yolov8-custom-segmentation/blob/main/r7.png)

## Model Performance
The performance of our model is evaluated with various metrics. mAP50 and mAP50-95 metrics assess the accuracy of our model's detection results. High mAP values indicate a more accurate model.

In our latest training output, the overall mAP50 value was determined as 0.942 and the mAP50-95 value as 0.937. This indicates that our model detects and segments objects with a high degree of accuracy in general.

When we evaluate the performance of our model for each food item separately, we see that the mAP50 and mAP50-95 values are quite high for most items. Especially for jam, pasta, and rice, these values are specified as 0.995, indicating that the model detects and segments these items with a very high level of accuracy.



## Confusion Matrix
![CMatrix](https://github.com/meryemsakin/yolov8-custom-segmentation/blob/main/r8.png)



### Results
<table>
  <tr>
    <td>YOLOv8s Object Tracking</td>
    <td>YOLOv8m Object Tracking</td>
  </tr>
  <tr>
    <td><img src="https://github.com/meryemsakin/yolov8-custom-segmentation/blob/main/rs.jpeg" width="600" height="400"></td>
    <td><img src="https://github.com/meryemsakin/yolov8-custom-segmentation/blob/main/r6.jpeg" width="600" height="400"></td>
  </tr>
    <td><img src="https://github.com/meryemsakin/yolov8-custom-food-item-detection-segmentation/blob/main/r4.jpeg" width="600" height="400"></td>
    <td><img src="https://github.com/meryemsakin/yolov8-custom-food-item-detection-segmentation/blob/main/r5.jpeg" width="600" height="400"></td>
 </table>
