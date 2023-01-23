<h1>Freshwater Quality Prediction</h1>
<p> Classifying whether a sample of freshwater is safe to drink or not</p>
<p> The dataset used had around 5.9M samples distinguished by 21 features.<a href="https://s3-ap-southeast-1.amazonaws.com/he-public-data/datasetab75fb3.zip">It can be found here</a></p>
Trained 2 models- Logistic Regression and LightBGM classifier<br>Logistic Regression yielded an accuracy of 76% while the LightBGM classifier produced an accuracy of 86%
Used Simple Imputer for imputation of corrupted values and minmax scaler for scaling
Dimensionality reduction was achieved using PCA.</p>
