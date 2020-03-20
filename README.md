# Human-Activity-Detection

#### In this module we trained a CNN to Recognize different Human Activities performed in Real Life from raw accelerometer signals collected from a smartphone. <br/> The model consists of one convolution layer followed by max pooling and another convolution layer. After that, the model will have fully connected layer which is connected to Softmax layer.  <br/> After running it for 5 epochs we  achieve <br/> Training Loss:  0.7445856 <br/> Training Accuracy:  0.871372 

## DataSet from WISDM: WIreless Sensor Data Mining
The Actitracker data set released by Wireless Sensor Data Mining (WISDM) lab. 

http://www.cis.fordham.edu/wisdm/dataset.php

## DataSet Description 

This dataset contains six daily activities collected in a controlled laboratory environment. <br/>
The activities include jogging, walking, ascending stairs, descending stairs, sitting and standing. <br/>
The data is collected from 36 users using a smartphone in their pocket with the 20Hz sampling rate (20 values per second). <br/>

## Statistics
### Raw Time Series Data

Number of examples: 1,098,207 <br/>
Number of attributes: 6 <br/>
Missing attribute values: None <br/>

### Class Distribution <br/>
Walking: 424,400 (38.6%) <br/>
Jogging: 342,177 (31.2%) <br/>
Upstairs: 122,869 (11.2%) <br/>
Downstairs: 100,427 (9.1%) <br/>
Sitting: 59,939 (5.5%) <br/>
Standing: 48,395 (4.4%) <br/>
