# Hand-sizing_NexGenPPT_ISU
This repository pertains to the development of an AI system designed to detect hand size dimensions based on hand pictures. It is affiliated with NexGenPPT at ISU.

# Method we will use 
The method we will use will be the key point detection using the TensorFlow, refer to https://github.com/FanZhouVictor/Custom-keypoint-detection

# Model sequence of hand pictures: 
We have three different pictures of a single hand from different angles. Let's pay attention to the first type of pictures with the palm upside. 
# steps
## preparing dataset
### 1. Data collection
We currently have almost 200 groups of hand pictures; each group has three pictures of the same hand from different angles. 

### 2. Annotate the hand & get the annotated hand data
The annotation of the hand can use the coco-annotator: https://github.com/jsbroks/coco-annotator. 
Video Tutorial： https://www.youtube.com/watch?v=OMJRcjnMMok

### 3. Processing dataset. 

### 4. Generate TFrecord

### 5. Creating label map

## Model preparation

### 1.pretrained model

### 2.Parameter changes in config file

## training

## save model
