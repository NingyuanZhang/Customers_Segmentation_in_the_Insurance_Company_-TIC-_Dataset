# Customers_Segmentation_in_the_Insurance_Company_-TIC-_Dataset
## Dataset
In this research we have been using THE INSURANCE COMPANY (TIC) 2000 dataset. This real-life dataset
was published by Peter van der Putten, and owned by a Dutch data mining company Sentient Machine Research,
Amsterdam. 

TIC2000 dataset is available on: TIC 2000 homepage: http://www.wi.leidenuniv.nl/~putten/library/cc2000/,and
Edinburgh University http://www.inf.ed.ac.uk/teaching/courses/dme/html/datasets0405.html.

## Feature selection
Calculate the entropy of each feature and only pick the top 20 features.
## T-SNE method
Visualizing high-dimensional dataset using t-SNE and color each record by different features.
## K-means method
K-Means is a partitioning clustering algorithm, where each cluster is connected with a centroid or central point
(mean of points). During training each object assigned to a cluster with the closest centroid, usually Euclidean
distance is used. 
## SOM method
To simplify the presentation and explore meaningful relationships we had been using the Self Organized Maps (SOM) or Kohonen Maps. 
SOM is a type of artificial neural network which is trained using unsupervised learning. It consists of
two layers of units: a one-dimensional input layer and a two-dimensional competitive layer, organized
as a 2D grid of units. This layer can also be called output layer or computational layer. Each node on
the competitive layer is a neuron (for example, a 7*7 layer has 7*7 neurons), and each neuron is
associated with a "weight" vector. The “weight” vector has the same dimension as each input vector.
The learning process is as follows. The weights of the neurons are initialized to small random values,
when an input vector is fed to the network, its similarity to all weight vectors is computed. The neuron
whose weight vector is most similar to the input is the winner and the winner is considered to represent
the input vector and other similar ones. The weights of the winner neuron and its neighbor neurons
would be adjusted towards the input vector. This process is repeated for each input vector for a large
number of times.
