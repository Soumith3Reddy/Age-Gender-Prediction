# Age-Gender-Prediction
Predict age and gender of people using mobile net v2 and UTKFace datasets with 91% accuracy age, 80% accuracy ethnicity, 47.45 MSE age.
___
## 1. Purpose and dataset
  - User gender and age are important for organizations to understand their customers and develop their strategies to provide better services to customers.
  - In the above project, we will discuss the issue of using the mobile net v2 model to predict the age, gender and ethnicity of customers entering the camera area.
  - In this article, we use the UTKFace dataset that includes more than 20,000 face images including annotations about age (0 - 116), gender (2) and ethnicity (5). The images include great variation in pose, facial expression, resolution,...
  - original dataset: [link](https://www.kaggle.com/datasets/jangedoo/utkface-new) The FC layer will use additional l2 regularizers.
## 3. Inference
- Model Predict age:
  + MSE predict age:
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/image/MSE_loss_age.png)
- Model predict gender:
  + Accuracy predict gender:
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/image/Accuracy_gender.png)
  + Loss predict gender:
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/image/Loss_gender.png)
- Model predict ethnicity:
  + Accuracy predict ethnicity:
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/image/Accuracy_ethnicity.png)
  + Loss predict ethnicity:
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/image/Loss_ethnicity.png)
- Test model:
Image: General Secretary Nguyen Phu Trong visit becomes Chinese
  + Before
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/test.jpg)
  + After
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/image/test/test.jpg)
  + Before
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/test1.jpg)
  + After
  <br>![image](https://github.com/Soumith3Reddy/Age-Gender-Prediction/blob/main/image/test/test1.jpg)
