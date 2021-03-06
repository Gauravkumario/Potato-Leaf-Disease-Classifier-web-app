# Potato Leaf Disease Classification

<p align="center">
  <img class="center" src ="https://thepracticalplanter.com/wp-content/uploads/2021/09/IS-Potato-Plant.jpg" alt="Drawing" style="width: 1400px; height: 600px">
</p>

<b>Description : </b> Here I used __Artificial Intelligence__ in diagnosing plant diseases. Various diseases like early blight and late blight immensely influence the quality and quantity of the potatoes and manual interpretation of these leaf diseases is quite time-taking and cumbersome. Therefore I created a __Web App__ using <b>Streamlit</b> which simply classify <b>Potato Leaf Diseases</b> and, finally deployed the Web-app on __Heroku__. Internally, our model is built using a simple <b>Convolutional Neural Network Architecture</b> to classify <b>Potato Leaf Diseases</b>. Initially I collected ready-made data from internet. Then due to small size of dataset, I used one of the simple and effective method, called <b>Data Augmentation</b> to increase the size of dataset as well as to reduce overfitting of our model. At the end built a __Deep Learning Model__ to detect or classify Potato Leaf Diseases and got a __test accuracy of 97%.__

<b>Heroku App : https://potato-leaf-cnn.herokuapp.com/</b><br>
<b>Dataset Source : https://www.kaggle.com/arjuntejaswi/plant-village</b><br>

<b>Folder Structure : </b>
```
                    Potato Leaf Dataset       --> main folder
                      ----| train      
                          ----| Potato_Healthy
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Early_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Late_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg

                      ----| test      
                          ----| Potato_Healthy
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Early_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Late_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                              
                      ----| valid      
                          ----| Potato_Healthy
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Early_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Late_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
```

<b>Sample Output : </b> The output is showing 3 thing's. 
* <b>Predicted Class : </b>The model's output.
* <b>Actual Class : </b>The actual output.
* <b>Confidence : </b>How confident our model is.
 
  
<p align="center">
  <img class="center" src ="/main/sample/potato.png" alt="Drawing" style="width: 1400px; height: 800px">
</p>

