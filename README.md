# Entity-Resolution-for-Web-Product-Duplication-Based-on-Blocking-Scheme
Code for thesis of Entity Resolution for Web Product Duplication Based on Blocking Scheme
All the code is written by python 3 and present in Jupyter notebook

## Algorithm explanation
### Algorithm 1: Data cleaning and shop dictionary summairzing
In algorithm 1 we do the basic cleaning for the given data set, and summarize all the keys and values of each weh shop into a shop_key_dictionary.

### Algorithm 2: Shop dictionary processing
In algorithm 2, we propose the code to process the shop dictionary, define the data type of the key, generate the string values and double values and key diversity , key dimension, and std.

### Algorithm 3: Forming the Aligned key set
In algorithm 3, we proposed a program to calculate the key similarity and form the aligned key set.

### Algorithm 4: Shops data restructure
In Algorithm 4, we would like to extract the product brand as a product feature variable, and restructure the product data based on their shop.

### Configuration combination
In configuration combination part, we propose our blocking schemes framework, including the blocks extractors, block transformers, and block aggregaters. In the end we export each configuration as individual data set.

### Algorithm_5
In algorithm 5 we propose the Multiple component Similarity Method (MSM) for the overall dataset and propose the grid research of 10 bootstraps to determine the optimal value for all the threshold.

### Algorithm_5 for blocked pairs
In algorithm 5 for blocked pairs, we apply the MSM to the data set after the blocking schemes preselection. In this section we go through all the configurations and select the configurations that perform well in both PC and RR. In the end, we apply another 10 bootstraps for the well-performed configurations and visualize their distributions.


## Running the code
To run the code, you need to download the code and dataset, adjust the data importing part of the code so you can import the dataset, and fun the code in the following order:
Algorithm 1 - Algorithm 2 - Algorithm 3 - Algorithm 4 - Configuration combination - Algorithm_5 - Algorithm_5 for blocked pairs

