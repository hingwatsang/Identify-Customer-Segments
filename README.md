# Identify-Customer-Segments

<b> Project Overview </b> </br>
In this project, I worked with real-life data provided to us by our Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. My job as a data scientist was to use unsupervised learning techniques to organize the general population into clusters, then used those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, you also needed to assess and clean the data in order to convert the data into a usable form.
</br>


<b> Step 1: Preprocessing </b> </br>
Before I started an analysis, I first explored and understood the data that you are working with. In this (and the next) step of the project, I worked with the general demographics data. As part of my investigation of dataset properties, I attended to a few key points: </br>
I created a cleaning procedure that I applied first to the general demographic data, then later to the customers data.

<b> Step 2: Feature Transformation </b> </br>
Now that my data is clean, I used dimensionality reduction techniques to identify relationships between variables in the dataset, resulting in the creation of a new set of variables that account for those correlations. In this stage of the project, I attended to the following points: </br>

<li> The first technique that I should perform on my data is feature scaling. </li>
<li> Once I scaled my features, I can then apply principal component analysis (PCA) to find the vectors of maximal variability. </li>
<li> I used the sklearn library to create objects that implement my feature scaling and PCA dimensionality reduction decisions. </li>
</br>

<b>Step 3: Clustering</b></br>
Finally, on my transformed data, I applied clustering techniques to identify groups in the general demographic data. I then applied the same clustering model to the customers dataset to see how market segments differ between the general population and the mail-order sales company. I tackled the following points in this stage:
</br>
<li> Use the k-means method to cluster the demographic data into groups. </li>
<li> Apply the techniques and models that I fit on the demographic data to the customers data: data cleaning, feature scaling, PCA, and k-means clustering. </li>
<li> Compare the distribution of people by cluster for the customer data to that of the general population. </li>
</br>
Sklearn was used in this part of the project, to perform my k-means clustering. In the end, I exported the completed notebook with my work as an HTML file, which will serve as a report documenting my approach and findings.

