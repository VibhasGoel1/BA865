# BA865


BA865: Final Project Proposal


Problem Definition

According to the Centers for Disease Control and Prevention (CDC), approximately 28.8 million reported hearing loss and 7.5 million people in the United States have some form of speech disability. Majority of these people use sign language to communicate. As such, individuals with limited or no knowledge of sign language often don’t understand and face difficulty in communicating with them (Alys Young and Bogusia Temple, 2014).

Through our analysis, we aim to build a CNN model that produces real-time sign language detection for easier interpretation and communication.


Prediction Task

Through our modeling and prediction, the real-time sign language detection tool will overcome the communication barrier. We will be using approximately 3-5 images of different positions and angles for each label and input these images with labels into the CNN model. For instance, feeding in 3-5 different “hello” sign images for the image label.

Motivation & Novelty

Through research and analysis, we found that millions of Americans and people worldwide use sign language primarily as a way of communication and people with no sign language knowledge face difficulty in communicating with them. The model will also serve as a supplementary tool for interpreters, assisting them in accurately conveying the intended meaning. 

This is the gap that the team wants to bridge. We envision a society where everyone, especially people with hearing or speech impairments, can communicate easily with one and all. 

Data

The team will be using image data and feed into the CNN model. The input data will be the ASLLRP (American Sign Language Linguistic Research Project) Sign Bank dataset and we can also generate more input data ourselves, if required. The dataset contains different images of each label.

Data Source: http://dai.cs.rutgers.edu/dai/s/signbank





Data Collection
3-5 images per label. Once images are extracted, we will label all the images respectively. 
ASLLRP Sign Bank



ata (2)
 
·   	What data will you use in your project? (Note: do not obtain your dataset from a Kaggle competition or the UCI machine learning repository; typically, people will have posted code solutions, e.g., on Kaggle, implementing prediction solutions, often with neural nets).
·   	Provide a link to the dataset or, if the data is not publicly available, provide a sample.
·   	Provide some descriptive information about the data (e.g., is it video, audio, text? How many observations are there?)
Pre-processing -

1.	Color from images
2.	Scaling on the important aspect of the image (For instance, focus on hand in the image)
3.	Thresholding and Gaussian Blur Filter to recognize the boundaries of the image and improve the clarity

Train Model

Predict Output - 
Using openCV and python modeling, we will be able to generate output on new data in real-time while facing the camera/webcam and can detect different sign language poses.

According to the Centers for Disease Control and Prevention (CDC), approximately 7.5 million people in the United States have some form of speech disability, which includes people who are mute or have limited speech. However, it's important to note that not all individuals who are mute have a speech disability, as some may choose to communicate through other means such as sign language or writing.


https://www.cdc.gov/ncbddd/disabilityandhealth/infographic-disability-impacts-all.html#speech


One in five people in the UK are deaf, rising to 70% in people over the age of 70,1 accounting for 12 million adults with hearing loss greater than 25 decibels hearing level (dB HL). A 2011 UK Census reported 22,000 residents reporting sign language as their main language, with the majority using British Sign Language (BSL).

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8313197/


http://dai.cs.rutgers.edu/dai/s/signbank




















BA865: Final Project Proposal
 

·   	What is the prediction task you hope to address, exactly? What are the predictors, and what are the labels?
·   	(Note: the predictor set should be comprised of unstructured data, e.g., text, audio, image, or video. Text or image will be the easiest to work with.)
 	 We are predicting the meaning of sign language based on given images of various signs. The predictor consists of pictures representing different signs, while the label corresponds to the meaning of each sign.	 
Motivation & Novelty (2)
 
·   	Why is it important or useful to address this prediction task? Who would find your model useful and in what settings? (Note: ideally, you will do a little background research on the topic).
·   	Is the task / data combination novel / new?
 	By accurately predicting sign language meanings from images , a reliable model can help bridge the communication gap between hearing and non-hearing individuals. The model can serve as a supplementary tool for interpreters, assisting them in accurately conveying the intended meaning. 
While predicting the meaning of sign language from images has been studied and explored previously, new datasets or novel techniques can still contribute to the field by improving the accuracy and efficiency of existing models.	 
Data (2)
 
·   	What data will you use in your project? (Note: do not obtain your dataset from a Kaggle competition or the UCI machine learning repository; typically, people will have posted code solutions, e.g., on Kaggle, implementing prediction solutions, often with neural nets).
·   	Provide a link to the dataset or, if the data is not publicly available, provide a sample.
·   	Provide some descriptive information about the data (e.g., is it video, audio, text? How many observations are there?)
 	 http://dai.cs.rutgers.edu/dai/s/signbank

ASLLRP Sign Bank
	 
 
Total	 
 	/5
 

























 
