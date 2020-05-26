# Bonjour !
Hello there and thanks for stopping by. My ongoing work in Python and R is showcased here. These are projects done out of my personal interests. I have kept my work as original as practically possible, but in this world of google ... allow me to acknowledge the contribution of others whose code may have found in here unconciously! Feel free to explore the repositories on your own or better still, start here to navigate. 

# Implementation of Linear Regression Model
The implementation calculates linear regression cofficients and slope of a list of Xs and ys. This is a reimplementation of gradient descent and optimiation to reach the minimum loss point quicker. For a point (a,b) loss at this point and 8 points surrounding this (a+/-delta, b +/- delta) is calculated. The point where maximum loss is found is picked and moved to as the new (a,b). This is then continued with optimiations to move to a local minimum. The slope and coefficient at the local minimum is the solution of the linear regression model. 
Code: [sglearn.linear_model]{https://github.com/shankar-sg/pyRepo/blob/master/sglearn/sglearn/linear_model.py}

# Implementation of KNN
The implementation does classifications using distances between the predicted point and various other already classified points. Eucledian distance between the new point (a,b) and N of the nearest , but already classified points are measured. A majority voting technique is used for classifying the newest point

# Implementation of RandomForest
Working progress

# Implementation of Leaves Classification using Keras/Tensorflow
A test set of 103 different leaves images has been captured by my kid using his nokia 3310. The images have been transferred and loaded into the github repository as test and train datasets. Train-set uses 93 images of 3 different types of leaves. Test is 10 leaves. A TensorFlow and Keras based sequence has been built to train the leaves images. The images are converted to a gray-scale image rather than a color image as the shape was the easiest classification attribute. The prediction after 20 epoch is more than 98%
