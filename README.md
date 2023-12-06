# PDDFA (Plant Disease Detection And Faramer Asistant)


## ABSTRACT
<p align="justify">
In the realm of agriculture, where the importance of sustainable practices looms large, the timely detection of diseases in crop production emerges as a critical factor for increasing productivity. However, Due to the scarcity of technologies used in crops, the diagnosis of diseases and pests is largely supported by human inspection, generating errors caused by the subjectivity of individuals. Even if disease is detected, finding the optimal treatment among the thousands of fertilizers and agricultural medicines is a challenging task.
</p>
Our goal is to develop a plant disease detection system that utilizes a subfield of artificial intelligence known as Computer Vision to solve this issue. This system can predict plant disease by comparing the images of plants and which those in the database then recommend the best treatment.
</p>
<p align="justify">
The system utilizes an algorithm to analyze and process the captured image to classify the plant disease as: The diagnostic system is composed of image acquisition, image preprocessing, segmentation, feature extraction, feature selection, and subsequent classification of disease. The system can recognize the condition by utilizing deep computer vision with convolutional neural networks (CNN) which is particularly well-suited for image recognition and processing tasks.
By utilizing a smartphone camera or a captured image, recommendations can be made to the agricultural shop where they will be available. on the other hand, the application will help the farmers with the information needed to treat the detected diseases produced by the image processing model. This solution aims to provide a versatile, scalable, approach to plant disease.
</p>

<p align="justify">
Overall, the system promises to enhance the process of detecting plant diseases and pests, while also providing farmers with information to enhance crop productivity, which will lead to a decrease in financial losses.
</p>

Keywords: Smart Plant Disease Detection, Pests, Farmer, Plant, Smartphone Camera, CNN, Mobile Application. 

## 1  CHAPTER 1: INTRODUCTION


<p align="justify">
Throughout history, humans have been developing tools and techniques to enhance agricultural productivity. From simple farm tools and organic fertilizers to greenhouses, tractors, chemical fertilizers, and other inventions made by humans. The most important part of the process of increasing agricultural productivity is maintaining the health of crops and providing farmers with the best treatment. The process of maintaining plant health includes appropriate fertilizers and medications. The detection of plant disease and its treatment is not easy process, it needs an experienced agronomist who has knowledge of all aspects of plants. 
</p>
<p align="justify">
With the help of machine learning and deep learning, the agricultural industry has become more advanced. Machine learning and deep learning have become one of the most important subfields of artificial intelligence through which systems are developed that do not need humans to perform their assigned tasks. Not to mention the speed and accuracy of the results possessed by these modern technologies, the results may not be as accurate if the person performed them himself. These technologies came trying to replace human work to reduce effort, budget, time and increase the productivity.
</p>
<p align="justify">
So, why deep learning in plant disease detection? Because the traditional way of predicting plant diseases requires full knowledge of plants. Human inspection can make mistakes in predicting many diseases and provide the best treatment that needed. In the other hand, the process of detection and prediction of the disease is much faster and much accurate when using deep learning and computer vision. All you need is a camera to predict the disease and provide treatment in less than a minute. In dealing with this issue, the system will use sub-field of Artificial Neural Network (ANN) called Convolutional Neural Network (CNN) which is particularly well-suited for image recognition and processing tasks. The process includes the image acquisition, image preprocessing, image segmentation, feature extraction, feature selection and subsequent classification of disease.
</p>


### 1.1 Problem Statement and purpose
<p align="justify">
The process of plant diagnosis through observation of the symptoms on plant leaves is full of complexity. Experienced agronomist and plant pathologists struggle to diagnose specific disease, and that lead to make mistakes in predictions of plant treatment process. Without the use of advanced diagnostic tools and automated computational systems for the detection and diagnosis of plant diseases, the errors are more likely to occur. These technologies play an important role for agronomist and pathologists to assist them in the process of detecting plant pests and diseases. 
</p>
<p align="justify">
Traditional methods often rely on human experts like agronomist and pathologists to diagnosis the plant pests and diseases, and that could be a long-time process, and can lead to errors due to variations in human judgment. The time an expert spends predicting the disease could lead to an increase in the spread of diseases. Moreover, when dealing with a diverse range of plant species and potential issues, manual inspection may result in inaccuracies. In Addition, the process of manual diagnosis of the plant need a laboratory analysis and this process may require substantial time, manpower, and equipment. Anyway, the plant disease is a huge impact for human around the world,  Our yield loss (range) estimates at a global level and per hotspot for wheat (21.5% (10.1–28.1%)), rice (30.0% (24.6–40.9%)), maize (22.5% (19.5–41.1%)), potato (17.2% (8.1–21.0%)) and soybean (21.4% (11.0–32.4%)) suggest that the highest losses are associated with food-deficit regions with fast-growing populations, and frequently with emerging or reemerging pests and diseases [1].
</p>

<p align="justify">
Building a mobile application that detect the plant disease could be a valuable tool for farmers. It helps the farmers to reduce the expected time of diagnosis and saves their money. The application employs image processing to extract visual features, including color, texture, and patterns, from plant images which are taken from phone camera or form the gallery. Then a pre-trained CNN model is used to analyze these features and classify plant diseases. 
</p>


### 1.2 Project and Design Objectives
* Develop a user-friendly mobile application that can detect plant diseases with high accuracy and a short diagnosis time. 
* Use image processing algorithms to extract visual features from plant images side by side with pre-trained CNN model to classify plant diseases.

### 1.3 Intended Outcomes and Deliverables 
<p align="justify">
The desired outcome from this project is a mobile application that provide the farmers the ability of detecting of plant disease, which save time, effort, and money. In addition, application will provide the farmers the common treatment of specific plant disease. The application is as an assistant for the farmers which reduce the need of experts which there's no need to waste much time in trying to predict the desired disease within the possibility of errors occurs.
</p>

