# Supervised and Unsupervised Learning in GIS 

Topics:
- image classification 
- supervised and unsupervised classification 
- examples 

Image Classification 
- the most commonly used ML in GIS
- automated approach for classifying raster images 
- uses multispectral (and other GIS data) as input 
- separate different classes based on pattern recognition 
- each pixel is assigned to particular theme or 'class' 

An agricultural land use map can be determined using the Random Forest Algorithm.  

Unsupervised:
- defined number of classes
- statistical methods to separate data values
- often first step of classification 
- analyst has no control 
- e.g. K-means

Supervised:
- User determines test areas (training sites or labeled data)
- prior knowledge of land cover
- defined number of classes
- e.g. Random Forest, Neural Networks 


Common Supervised Learning Algorithms:
- Nearest Neighbor
- Logisitic Regression
- Decision Trees
- Linear Regression 
- Support vector machines
- Artificial neural networks
- Random forests 

Unsupervised learning:
- K-means clustering
- ISODATA
- Association Rules

LLMs are typically unsupervised. Initial process is unsupervised. Then fine-tuning is performed using supervised learning techniques.


Image Classification:
- how accurate is the classified image
- need 'truth data' -- sample of pixels of known classes
- truth data can be: another map, field samples, ariel images, etc.
- method: confusion matrix! (assesses accuracy)

usually threshold for accuracy is 85%.

8:41
