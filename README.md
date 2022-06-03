# DOG_BREEDS_SEARCH_ENGINE
Exam of Multimedia Information Retrieval and Computer Vision

“DOG_BREEDS_SEARCH_ENGINE” is a search engine that recognize dog breeds image inserted by the user, from a set of 120 different dog breeds. 
We used a pre trained Deep Neural Network “DenseNet121” to extract features from the dataset “Dog_Breeds” and the distractor “MirFlickr”. We decided to extract the features using a finetuned model that we created, we implemented our version of LSH-Index to enable fast similarity search on deep features. We measured the performance with LSH index and with a brute force approach, to compare the results. To explore our solutions, we create a simple web-interface that after the insertion of an image, prints out the 10 most similar results.
