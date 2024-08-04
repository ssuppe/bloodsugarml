# bloogsugarml
My colabs and analysis of my blood sugar levels over time, learning how to apply ML/AI methods

The main goal is to re-acquaint myself with modern libraries for regression, neural networks and (ultimately) LLMs.

I am studying the [Machine Learning Crash Course with TensorFlow APIs](https://developers.google.com/machine-learning/crash-course). 
My general approach is to do the lessons and then re-apply to my blood sugar levels to see if I can improve prediction.

## Table of Contents

| Notebook | Description |
| -------- | ----------- |
|[1) Blood Sugar ML Investigation Linear Regression Model](https://github.com/ssuppe/bloogsugarml/blob/main/1\)_Blood_Sugar_ML_Investigation_Linear_Regression_Model.ipynb) | Initial investigation of linear regressions of current blood sugar to historical (T-60+) blood sugars, and deltas |
|[1a) Blood Sugar ML Investigation Linear Regression Model](https://github.com/ssuppe/bloogsugarml/blob/main/1a\)_Blood_Sugar_ML_Investigation_Linear_Regression_Model.ipynb) | Extension to #1, but also using historical insulin-on-board, basal IOB and activity (essentially rate of insulin absorption from previous period) |
|[2) Blood Sugar ML Investigation Linear Regression Model]([https://github.com/ssuppe/bloogsugarml/blob/main/1a\)_Blood_Sugar_ML_Investigation_Linear_Regression_Model.ipynb](https://github.com/ssuppe/bloogsugarml/blob/main/2)_Binary_Classification_of_Diabetes_diagnosis.ipynb)) | Binary classification. In this case I couldn't think of a useful exercise to apply to my own data, so instead I used a freely available Diabetes dataset from OpenML, originally from the National Institute of Diabetes and Digestive and Kidney Diseases. It has health indicators and results from ~1000 women (glucose, insulin, but also blood pressure, etc, with an outcome label of whether or not they have diabetes - probably type 2 in most cases). I used this to create a model with ~50% precision but ~100% recall. While 50% precision is quite low, in some circumstances this could be useful as a way to cheaply pre-screen patients with common medical test results to determine who needs to come in for further (and possibly more expensive) testing.  |
