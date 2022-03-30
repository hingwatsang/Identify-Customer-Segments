# Identify-Customer-Segments

<b> Project Overview </b> </br>
In this project, I worked with real-life data provided to us by our Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. My job as a data scientist was to use unsupervised learning techniques to organize the general population into clusters, then used those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, you also needed to assess and clean the data in order to convert the data into a usable form.
</br>


<b> Step 1: Preprocessing </b> </br>
Before I started an analysis, I first explored and understood the data that you are working with. In this (and the next) step of the project, you’ll be working with the general demographics data. As part of your investigation of dataset properties, you must attend to a few key points:
You will create a cleaning procedure that you will apply first to the general demographic data, then later to the customers data.

Step 2: Feature Transformation
Now that your data is clean, you will use dimensionality reduction techniques to identify relationships between variables in the dataset, resulting in the creation of a new set of variables that account for those correlations. In this stage of the project, you will attend to the following points:

The first technique that you should perform on your data is feature scaling. What might happen if we don’t perform feature scaling before applying later techniques you’ll be using?
Once you’ve scaled your features, you can then apply principal component analysis (PCA) to find the vectors of maximal variability. How much variability in the data does each principal component capture? Can you interpret associations between original features in your dataset based on the weights given on the strongest components? How many components will you keep as part of the dimensionality reduction process?
You will use the sklearn library to create objects that implement your feature scaling and PCA dimensionality reduction decisions.

Step 3: Clustering
Finally, on your transformed data, you will apply clustering techniques to identify groups in the general demographic data. You will then apply the same clustering model to the customers dataset to see how market segments differ between the general population and the mail-order sales company. You will tackle the following points in this stage:

Use the k-means method to cluster the demographic data into groups. How should you make a decision on how many clusters to use?
Apply the techniques and models that you fit on the demographic data to the customers data: data cleaning, feature scaling, PCA, and k-means clustering. Compare the distribution of people by cluster for the customer data to that of the general population. Can you say anything about which types of people are likely consumers for the mail-order sales company?
sklearn will continue to be used in this part of the project, to perform your k-means clustering. In the end, you will export the completed notebook with your work as an HTML file, which will serve as a report documenting your approach and findings.

Step 4: Review and Submit the Project
Before you submit your project for review, you should first review the project rubric. Your project will be evaluated by an Udacity reviewer using this criteria, so you should make a self-evaluation as well. In order for your project to pass review, it must meet all specifications.

Once you are ready for project submission, export an HTML version of your notebook and add to your workspace submission, then submit your entire project from the workspace using in the button in the bottom right.
