# **Project Title**

### A machine learning approach to detect red cars in high resolution satellite images ###

### **Breif Description about the project**

In this project we aim to detect all the red cars in a test image by training the RGB features of pixels to a KNN classifier. To reduce the computational time of training all the pixels, we add a preprocessing step to by building a small square around the image and then training it. 


### **Parameters**

```
Size: size of the small sqaure to be constructed
k: number of nearest neighbors in KNN algorithm
```

The optimal parameters are:
```
size: 10 - 50
k : 2 - 4
```

### **How to run the file**

```
python run.py
```

## **Description of the py files**

* run.py - wrapper funtion which call functions in train.py and test.py
* Train.py - preprocessing step with training
* Test.py - used to reshape the test image and send it for testing

