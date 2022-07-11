# A-Deep-Visual-Learning-based-Recommendation-System
The recommendation System proposed makes use of social media analytics based centrality measures property to propose a model which adds to the completeness of an image. For e.g. A man with white Shirt and black coat can get a recommendation of a tie. Basically, images are fed into the model as input. Each image containing more than one object gives some information about the co-occurrence of the two objects. The model uses this criterion to build a weighted graph with the weights equivalent to frequency of co-occurrence of the two objects. Further, this weighted graph is used to find nearest neighbours and then neighbours having highest centrality measure values are recommended. An attempt is being proposed to modify this idea further based on area of the images and other phenomena involved. 

Base Source : https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9741455
