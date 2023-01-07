# **Alzheimer-s-Prediction-Model** #
<br />
Alzheimer's disease is a progressive neurologic disorder that causes the brain to shrink (atrophy) and brain cells to die. Alzheimer's disease is the most common cause of dementia — a continuous decline in thinking, behavioral and social skills that affects a person's ability to function independently.
Approximately 5.8 million people in the United States age 65 and older live with Alzheimer's disease. Of those, 80% are 75 years old and older. Out of the approximately 50 million people worldwide with dementia, between 60% and 70% are estimated to have Alzheimer's disease.
The early signs of the disease include forgetting recent events or conversations. As the disease progresses, a person with Alzheimer's disease will develop severe memory impairment and lose the ability to carry out everyday tasks.
Medications may temporarily improve or slow progression of symptoms. These treatments can sometimes help people with Alzheimer's disease maximize function and maintain independence for a time. Different programs and services can help support people with Alzheimer's disease and their caregivers.
There is no treatment that cures Alzheimer's disease or alters the disease process in the brain. In advanced stages of the disease, complications from severe loss of brain function — such as dehydration, malnutrition or infection — result in death.
<br />
![dataset-cover](https://user-images.githubusercontent.com/58718943/211048981-6a82f86c-afd3-4346-9a93-6731ca2fa02c.jpg)
<br />


### **Identifying stage of Alzheimer's using CNN** ###

In this notebook, we build a convolutional neural network to predict the severity of Alzheimer's using MRI images. 
The dataset is available on Kaggle (https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset-v2) and consists 
of four classes, i.e., mildly demented, moderately demented, non-demented, and very mildly demented, and contains 35840 training images and 6400 test images.
Additionally, images come in different resolutions, thus an ImageDataGenerator is used to feed this information to the convolutional neural network. 
<br />
With the size and complexity of the dataset in mind, CNN's architecture with 17,360,420 parameters was built. <br />
Below is a brief summary of CNN's architecture. <br />
<br />
![parameter](https://github.com/priyanshusingh-collab/Alzheimer-s-Prediction-Model/raw/main/alzheimers%20summary.png)
### **Results** ###

![parameter](https://github.com/priyanshusingh-collab/Alzheimer-s-Prediction-Model/raw/main/alzheimer_trainingaccuracy.PNG)
<br />
![parameter](https://github.com/priyanshusingh-collab/Alzheimer-s-Prediction-Model/raw/main/alzheimer_validationaccuracy.PNG)
<br />
![parameter](https://github.com/priyanshusingh-collab/Alzheimer-s-Prediction-Model/raw/main/alzheimer_trainingloss.PNG)
<br />
![parameter](https://github.com/priyanshusingh-collab/Alzheimer-s-Prediction-Model/raw/main/alzheimer_validationloss.PNG)
<br />

At 20 epochs, <br />
Training accuracy:  99.40% <br />
Validation accuracy: 99.20% <br />
Training loss: 0.0400 <br />
Validation loss: 0.0238 <br />
