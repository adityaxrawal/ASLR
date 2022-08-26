# ASLR
**American Sign Language Recognition**
American Sign Language (ASL) is the primary language used by many deaf individuals in North America, and it is also used by hard-of-hearing and hearing individuals. 
The language is as rich as spoken languages and employs signs made with the hand, along with facial gestures and bodily postures.

In this project, you will train a convolutional neural network to classify images of ASL letters. After loading, examining, and preprocessing the data, you will 
train the network and test its performance.

# **TOOLS USED**
1. Python
2. OpenCV 
3. TensorFlow
4. Keras

# **To Run the Project:**
**Step 1:** Install Python and its libraries needed which are OpenCV, TensorFlow and Keras.

**Step 2:** Now you have to train the model. For this run:

```
python cnn_model.py
```

**Step 3:** Now your model has been trained. To test the model you have to run recognise.py.

```
python recognise.py
```
Adjust the HSV values from the track bar so that your hand can be recognised by the model.

   L-H 0
   
   L-S 50
   
   L-V 0
   
   U-H:179
   
   U-S:255
   
   U-V239
   
These values are only suitable with a perfect white background.

**Step 4:** To create your own data set. Run:

```
python capture.py
```

Thank you for the visit.
