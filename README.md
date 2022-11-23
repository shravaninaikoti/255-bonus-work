# 255_bonous_work_plant_disease_classification

Task steps used:

1. data collection of plant disease images

2. data interpretation and preprocessing

3. train different models on the plant disease images and pick the model with best performance

4. save the model in .pb format 

5. Creating Rest API using Flask at backend to hit the model and get results.

6. web application creation to display results.

Datasets used: 

Link: https://www.kaggle.com/code/vad13irt/plant-disease-classification/data


#Deployment steps:

1. fork the repository using the github link

2. https://github.com/shravaninaikoti/255-bonus-work

3. In command prompt change the working directory to 255-bonus-work directory

4. Run the following command: >python3 app.py

5. If you get any module not found error try installing the module using: >pip3 install <module_name>

6. After successful execution, copy the local host link and run it in the browser.

#Working

1. On the home page you can observe an animation with predict disease button

![alt text](https://github.com/shravaninaikoti/255-bonus-work/blob/main/Screenshots/Screenshot%20(17).png?raw=true)

2. On clicking predict disease, you will be asked to give an image of plant leaf as input.

![alt text](https://github.com/shravaninaikoti/255-bonus-work/blob/main/Screenshots/Screenshot%20(19).png?raw=true)

3. After selecting the image and clicking of predict, the model will be hit and the predicted disease will be displayed along with it's description.

![alt text](https://github.com/shravaninaikoti/255-bonus-work/blob/main/Screenshots/Screenshot%20(20).png?raw=true)
