---
description: How I trained my model for Plate Detection and Character Recognition
---

# Model Preparation & Training

### Gathering Dataset

I gathered Dataset through Kaggle and Roboflow, then merged them into one project. I started annotating all the images with the help of Roboflow which took a considerable amount of time. After annotations were completed, to test out the model I simply utilized Roboflow for training. In terms of my project I used YOLOv8 as I had made it for my Project Specification.

<figure><img src=".gitbook/assets/image (5) (1).png" alt="" width="375"><figcaption></figcaption></figure>

<figure><img src=".gitbook/assets/image (7).png" alt="" width="375"><figcaption></figcaption></figure>

### Creating Custom Dataset

The custom dataset that was made through Roboflow, I exported it into the format of YOLOv8 through the Export feature in Roboflow. I uploaded the custom dataset to Google Colab and proceeded to train.

<figure><img src=".gitbook/assets/image (4) (1).png" alt=""><figcaption><p>Roboflow Docs for Exporting a Dataset</p></figcaption></figure>

### Roadblocks in Google Colab

Google Colab's feature that was a roadblock was that you had to pay a certain fee to utilize their powerful cloud GPUs and even had a limitation for the time you could use the free-tier T4 GPU. I could train my model for an epoch of 50. More epochs can result to higher accuracy for the model, so I would consider that would b e a roadblock. Training locally through Anaconda was a limitation too as my machine was not powerful enough.

<figure><img src=".gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption><p>Character Models Training &#x26; Results</p></figcaption></figure>

### Training & Post-training

After training completion I moved to Deployment where discovering Streamlit came in very handy. Streamlit is a Python framework that helps to showcase the powers of AI/ML through a web-app. To preview and utilize the models that was made through training in Colab, I fiddled around with it and made few Python functions that would help to integrate into my main front end app developed on Streamilt.&#x20;

<figure><img src=".gitbook/assets/image (3) (1).png" alt=""><figcaption><p>Using the model that recognizes characters in Nepali LPs</p></figcaption></figure>

<figure><img src=".gitbook/assets/image (2) (1) (1).png" alt=""><figcaption><p>Testing out the functions that helps in recognizing the characters within License Plates</p></figcaption></figure>





