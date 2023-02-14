<h2>Name: Mustapha Momoh</h2>
<h2>WATIAM: mmomoh</h2>
<h2>Student ID: 20986226 </h2>

<h3>The visualizations created by this application are 2D embeddings of the Fashion Mnist dataset.</h3>
<p>The dimensions have been obtained through principal components analysis(PCA),  t-Distributed Stochastic Neighbor Embedding (t-SNE), and Multidimensional Scaling (Mds). </p>


<h4>Structure of the application</h4>

1. `app.js` is the main application file and can be found in the root folder.
2. `preprocess.py` is the python script that preocesses the fashion mnist inorder to create the dimensions. 
3.  The `2D.html` file contains the code for the creating the three visualizations. 
4. The public folder contains the static files for the application

<h4>How to use the application. </h4>
* Open the terminal of your code editor and set the current working directory to the project root folder i.e. `momoh_20986226_VD2`.

* You may  skip this step and move to 3 since the a precomputed file `combined.csv` has been provided. However, if you choose to proceed, open the python script and hit run (there is a run button if you are using vscode). The script takes a while to run (at least 25 minutes). This script will create the embeddings and save the three pairs of dimensions and classes as columns in a csv file named `combined.csv`. The file will automatially be created in the `public` folder.

* From your terminal, type and run the command `npm start`
* Open a browser tab and type `localhost:3002`
* You will find the three visualizations titled appropriately on the page. Hover over the dots to see the interactivity of the plots.


<h4>Observations from the visualizations.</h4>
Upon examining the plots, it is evident that all three of them display a certain degree of clustering and separation between the different fashion classes. However, the t-SNE scatter plot demonstrates the most effective separation between the clusters. Additionally, it is consistently observed across all three plots that the clusters for fashion categories 7 (Sneaker) and 1 (Trouser) are the most compact, suggesting that the samples within these categories share a high degree of similarity, as expected. Furthermore, there is a considerable overlap between categories 4 (coat) and 2 (pullover), implying that these two categories share similar visual features. Finally, it is worth noting that, on average, the distance between the points in the shirts cluster (category 6) appears to be the greatest, indicating that shirts may have a diverse range of visual features and therefore, exhibit some dissimilarity.




