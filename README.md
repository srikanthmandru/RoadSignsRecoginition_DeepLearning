# RoadSignsRecoginition_DeepLearning

This project deals with recognition of road signs from the images. In machine learning terms, it is single-image, multi-class classification problem.

I found this problem interesting as it is subpart of building an autonomous driving vehicles and would help improve driving model to achieve better results. 

Dataset source : 
  http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset 
  
About data:
  There are 43 classes of road signs with more than 50,000 images in total. 
  
Models and approach: 

•	Pre-processed data using normalization technique (divide by 255) to standardize pixel values of images.

•	Implemented Shallow Neural Networks , Deep Neural Networks and Convolutional Neural Networks(CNN) using Keras package for python. 
For CNN, I built a customized model inspired from VGG16 architecture.

•	Evaluated models through accuracy as metric. Over all models, CNN has achieved good accuracy of about 93% on test dataset. 

•	I will try to tune existing models further and also implement other models to get better accuracy so that model would generalize well to unseen real-world data. Stay tuned!!!
  
