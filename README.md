# Deep Learning for Traffic Counting

Challenges with Traditional Methods:
Traditional methods using pneumatic tubes are prone to setup risks, wear-and-tear issues, and accuracy limitations. They are also not easily scalable for diverse traffic analysis needs.

Advantages of Computer Vision Approach:
Using deep learning and computer vision:

Reduced Risk and Maintenance: Cameras can be safely installed beside roadways without disrupting traffic.
Improved Accuracy: Deep learning models offer precise vehicle tracking and counting capabilities.
Scalability: Easily customizable for different vehicle types and scalable to include pedestrians, cyclists, and more.
Project Details:

Setup and Data: Utilizes publicly available surveillance camera datasets, annotated with bounding boxes for vehicle types.
Model Training: Implements transfer learning with YOLOv5 on the dataset to improve model accuracy for vehicle detection.
Experimentation: Conducts training over multiple epochs and evaluates model performance with metrics like precision, recall, and mAP@.5.
Real-time Inference: Demonstrates real-world applicability by testing against live traffic video streams.
Results:

Achieved significant improvements in vehicle detection accuracy through model training and optimization.
Demonstrated the capability to count and classify vehicles accurately in both controlled datasets and real-time scenarios.
Conclusion:
This project showcases the effectiveness of deep learning in enhancing traffic management through robust vehicle detection and counting solutions. By leveraging computer vision technologies, it addresses the limitations of traditional methods while paving the way for future advancements in smart transportation systems.

- The sample dataset is from [AI Hub 30743](https://aihub.or.kr/aidata/30743).
- models/yolov5s_highway.pt is the custom trained model with the sample dataset after 400 hundred epochs.
- The annotation xml file had to be converted to YOLO V5 format. The code can be found in the [Colab notebook]


Next Steps:
Further refinement and deployment of the model for broader applications including smart city initiatives and traffic flow optimization.


