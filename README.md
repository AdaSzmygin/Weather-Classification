The project presents a study whose aim is to classify photos showing weather conditions divided into 11 classes: snow, frost, rain, fogsmog, storm, dew, glaze, sandstorm, hail, rainbow and rime. 
The study solved several problems with the input data, the first of which was to standardize the shape and size of the images so that they were all square and of one size. 
The second problem solved was the transformation of photos so that they were all of the same type in terms of colors. Converted grayscale and alpha photos to three-dimensional RGB images. 
Then, it was checked how well the human brain copes with a given problem and for this purpose, a study was carried out on assigning images to classes.
In the next stage of the research, a training model was prepared using the CNN method, sequential model, maxPooling2D method, deep layer, Adam optimization method and the CategoricalCrossEntropy cost function. 
Finally, the results were checked using the following metrics: accuracy, precision and sensitivity, and the loss function for training and test data was checked on a graph. 
A histogram was also made showing which classes the model had the greatest and least problems with.
