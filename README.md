# Parkinson-drawing

Please find the dataset on https://www.kaggle.com/kmader/parkinsons-drawings 


This code use the same approach of  *_On the use of histograms of oriented gradients for tremor detection from sinusoidal and spiral handwritten drawings of people with Parkinson’s disease_*. First, I employed the Histogram of Oriented Gradients Image Descriptor (HOG) to extract the features and, next, I ran a Random Forest Classifier.

HOG is a structural description that captures and quantifies changes in the input image's local gradient. It was able to calculate how the directions of spirals and waves vary over time. Furthermore, HOG was able to determine whether these drawings have a "shake" to them, as one might expect from Parkinson's patients.




Good references of Papa J:

Pereira C, Pereira D, Papa J, Rosa G, Yang X (2016) Convolutional neural networks applied for Parkinson’s disease identification. In: Machine learning for health informatics. Springer, pp 377–390

Pereira C, Weber S, Hook C, Rosa G, Papa J (2016) Pereira C, Weber S, Hook C, Rosa G, Papa J (2016) Deep learning-aided Parkinson’s disease diagnosis from handwritten dynamics. In: Conference on graphics, patterns and ages. IEEE, pp 340–346

Afonso LCS, Pereira CR, Weber SAT, Hook C, Papa JP (2017) Parkinson’s disease identification through deep optimum-path forest clustering. In: 30th conference on graphics, patterns and images (SIBGRAPI). IEEE, pp 163–169


Pereira C, Pereira D, Rosa G, Albuquerque V, Weber S, Hook C, Papa J (2018) Handwritten dynamics assessment through convolutional neural networks: an application to Parkinson’s disease identification. Artif Intell Med 87:67–77

Afonso LC, Rosa GH, Pereira CR, Weber SA, Hook C, Albuquerque VHC, Papa JP (2019) A recurrence plot-based approach for Parkinson’s disease identification. Future Gener Comput Syst 94:282–292

Ribeiro LC, Afonso LC, Papa JP (2019) Bag of samplings for computer-assisted Parkinson’s disease diagnosis based on recurrent neural networks. Comput Biol Med 115:103477