# **Waste Management and Segmentation**
 One of the major problems faced by the world is the proper disposal of waste or effective waste management system. Apart from the common household, this problem is largely faced huge gatherings. The waste management hardships are catalysed by the large number of people, limited space for waste disposal, human interference in waste collection and disposal and the ignorance among the common people on the importance of waste segregation. We need solutions that are cost-effective, easy for people to use, and good for environment. Recommend a system which can automatically detect the distribution and monitoring of waste containers to determine their location and quantities of waste. This system can make your environment clean, healthier and sustainable. 
___
## **Idea**
My approach involves leveraging state-of-the-art technologies such as YOLOv7 and Detectrons2 to address the waste management challenge. By collecting a diverse dataset of images and videos depicting various waste products, including Plastics bottles, Plastic bags, Metal cans, and Electronic waste, I aim to train a robust model. This model will be capable of accurately classifying and detecting these different types of waste items. The objective is to create a predictive tool that assists in identifying and categorizing waste materials effectively, contributing to improve waste sorting and management practices.
___
## **Dataset**
For creating a model, data is very important. I used <a href='https://www.kaggle.com/'> Kaggle </a> for datasets and for more images i used <a href='https://www.google.com'> Google Images </a> .
___
## **Data Annotation**
Data Annotation is an intial stage of any detection. Data annotation is the process of labeling individual elements of training data to help machines understand what exactly is in it and what is important. This annotated data is then used for model training. There are many tools for data annotation but this three are quite popular:-
1. <a href='https://labelstud.io/'>Label Studio</a>
2. <a href='https://viso.ai/computer-vision/labelimg-for-image-annotation/#:~:text=LabelImg%20is%20a%20free%2C%20open,its%20GI%20(graphical%20interface'>Labelimg</a>
3. <a href='http://labelme.csail.mit.edu/Release3.0/'>Labelme</a>
___
## **YOLOv7**
<a href='https://github.com/WongKinYiu/yolov7'>YOLOv7</a> algorithms can be used to recognize and track objects as they move through a production line, allowing for more efficient and accurate manufacturing. Additionally, object detection is used for quality control and defect detection in products or components as they are being manufactured. In this project, i am using YoloV7 for train the model and predicate on the basis of that model.
___
# **Model**
* ## Model Training
  YOLOv7 is the fastest and most accurate real-time object detection model for computer vision tasks. YOLOv7 is the chosen models for addressing the waste classification challenge. The dataset consists of 480 images (120 images of each type) for training and 120 images (20 images of each type) for validation.
