# Cancer-detection-using-SVM
Train a model using a support vector machine approach to distinguish between benign and malignant cells using human cell records data. 

#### SVM
SVM categorises data points even when they are not otherwise linearly separable by mapping the data to a high-dimensional feature space. Once a boundary between the categories is identified, the data is altered to enable the hyperplane-like representation of the boundary. The group to which a new record should belong can therefore be predicted using the features of new data.

### About the dataset
The dataset that is publicly available from the UCI Machine Learning Repository (Asuncion and Newman, 2007)[http://mlearn.ics.uci.edu/MLRepository.html]. The dataset consists of several hundred human cell sample records, each of which contains the values of a set of cell characteristics. The fields in each record are:

|Field name|Description|
|--- |--- |
|ID|Clump thickness|
|Clump|Clump thickness|
|UnifSize|Uniformity of cell size|
|UnifShape|Uniformity of cell shape|
|MargAdh|Marginal adhesion|
|SingEpiSize|Single epithelial cell size|
|BareNuc|Bare nuclei|
|BlandChrom|Bland chromatin|
|NormNucl|Normal nucleoli|
|Mit|Mitoses|
|Class|Benign or malignant|
<br>
<br>

<p align="center">
  <img src="https://imgur.com/3qSnlLb.png" alt="dataset" />
</p>


### Evaluatiion 

<p align="center">
  <img src="https://imgur.com/2q4C85I.png" alt="Confusion matrix" />
</p>

