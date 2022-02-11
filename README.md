# meta-motion

In this project we used a MetaMotion bluetooth sensor to recognize 8 different hand movements.
The sensor provides data of linear and angular speed in 3 axis (X Y Z) each and a barometer sensor data.
Using this data we designed features to distinguish between different movements.
A tree ensemble was trained on those features creating a model for classification of the hand movements.

Our results are not very impressive due to poorly labeled data and poor construction of the features.
more work is needed in the signal processing part to build better and more reliable features for each movement.
