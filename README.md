# <h1 style="font-family:verdana; text-align: center;"> AI or Real? Image Classification Challenge </h1>

![robot.png](https://img.freepik.com/premium-photo/arafed-robot-painting-canvas-messy-room-with-window-generative-ai_927978-24454.jpg?w=1060)


## <h2>  <center> Where is the data coming from?</center> </h2>

<div class="alert alert-block alert-info" style="font-size:14px; font-family:verdana; line-height: 1.7em;">
    📌 &nbsp;In response to the rise of AI-generated images, our challenge is to develop a Convolutional Neural Network (CNN) model that distinguishes between authentic and AI-generated images, ensuring reliability in digital content.
</div>

<div style="color:white;
           display:fill;
           border-radius:5px;
           background-color:#5642C5;
           font-size:110%;
           font-family:Verdana;
           letter-spacing:0.5px">

<p style="padding: 10px;
              color:white;">
    <br>
📍Information about the data
    
Original data can be found at the following link. It contains more than 15,000 artwork images with each and every label verified:
https://www.kaggle.com/datasets/kausthubkannan/ai-and-human-art-classification/data    
</p>
</div>


## Data Visualization

<div class="alert alert-block alert-info" style="font-size:14px; font-family:verdana; line-height: 1.7em; background-color: #add8e6; color: #000000;">
    &nbsp; The two categories of the data are:<br>
    🔴AI_GENERATED<br>
    🔴NON_AI_GENERATED<br>
</div>
    <br>

![descarga](https://github.com/AndresMembrillo/AI_image_recognition/assets/145653361/d22477ee-9cfe-4c46-9786-1bc73e068d96)


## CNN Model

Project based on the implementation of Deep Learning models (Tensorflow and Keras) in images.

- Convolutional part. Pre-trained model: "vgg16":
    <br>  
  ![VGG](https://github.com/AndresMembrillo/AI_image_recognition/assets/145653361/154ed276-edf4-47dd-9a0c-f89b5a7a45c5)
    <br>
- Dense part:
    <br>
![simple](https://github.com/AndresMembrillo/AI_image_recognition/assets/145653361/724a7aa4-18e4-4793-b6cc-a04c7344a4ea)


## Model Performance Examples
![descarga (1)](https://github.com/AndresMembrillo/AI_image_recognition/assets/145653361/10a6d7e5-ac38-44ac-b89f-f744f5500ede)


## Metric for Evaluation
<div class="alert alert-block alert-info" style="font-size:14px; font-family:verdana; line-height: 1.7em; background-color: #3c0000; color: #f4f4f4;">
    📌 &nbsp; 
In a binary classification task like distinguishing between "AI_GENERATED" and "NON_AI_GENERATED" images, accuracy is a fundamental metric for evaluating model performance. It measures the ratio of correct predictions to the total number of predictions. With balanced class distribution, accuracy provides a comprehensive evaluation of the model's classification accuracy for both categories.
<br>
    
![accuracy](https://github.com/AndresMembrillo/AI_image_recognition/assets/145653361/14665aee-4613-46c9-b761-8fd155899a9e)



## Conclution
<blockquote><p style="font-size:16px; color:#159364; font-family:verdana;">💬 
The model has an accuracy of 0.90 with the data we have worked with. The current model is a prototype 1.0 that has been trained on AI-generated artwork images as well as non-AI-generated images. The goal is to train it with images from different segments. For example, it can compare AI-generated dog images with real dog images, or focus solely on comparisons among humans. The objective is to achieve a model that maintains consistent performance across different data types.</p></blockquote>
