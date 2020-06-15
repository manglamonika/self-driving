# Self-Driving-Car

# Project Description : 

In this project, I used a neural network to clone car driving behavior. It is a supervised regression problem between the car steering angles and the road images in front of a car. Those images were taken from three different camera angles (from the center, the left and the right of the car). As image processing is involved, the model is using convolutional layers for automated feature engineering.

# Training of the Model : 

I used more than 13,000 images of the road to train the self driving car. These images were taken from three different camera angles from the car. I used mean squared error for the loss function to measure how close the model predicts to the given steering angle for each image. I used ModelCheckpoint from Keras to save the model only if the validation loss is improved which is checked for every epoch.

# Screenshots :

![Capture](https://user-images.githubusercontent.com/42375851/84621655-c21ca100-aef8-11ea-9d48-f52fc1dc77ff.PNG)
![2](https://user-images.githubusercontent.com/42375851/84621861-3fe0ac80-aef9-11ea-9894-c5ade842cafb.PNG)
![3](https://user-images.githubusercontent.com/42375851/84621946-77e7ef80-aef9-11ea-9f2b-a5ba0c2c1066.PNG)
![4](https://user-images.githubusercontent.com/42375851/84622039-bb425e00-aef9-11ea-9a13-d24173b14889.PNG)
![5](https://user-images.githubusercontent.com/42375851/84622191-05c3da80-aefa-11ea-9a42-f6c7416f6274.PNG)
![6](https://user-images.githubusercontent.com/42375851/84622195-08becb00-aefa-11ea-8b9c-1cea76db91ea.PNG)
![7](https://user-images.githubusercontent.com/42375851/84622197-09eff800-aefa-11ea-89c2-db61534326cb.PNG)
![8](https://user-images.githubusercontent.com/42375851/84622199-0bb9bb80-aefa-11ea-8a4b-4936c603eae4.PNG)
![9](https://user-images.githubusercontent.com/42375851/84622203-0e1c1580-aefa-11ea-8eae-5beb52901f56.PNG)
![10](https://user-images.githubusercontent.com/42375851/84622221-14aa8d00-aefa-11ea-99f3-9660df07169b.PNG)



# Result : 

The car successfully steers across the track and predicts correct steering, speed, throttle, reverse, center, left and right values.


