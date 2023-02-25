# ProductAnalysis

![Project Image](project-image-url)

> This is a ReadMe template to help save you time and effort.

---

### Table of Contents
<!-- You're sections headers will be used to reference location of destination. -->

- [Description](#description)
- [How To Use](#how-to-use)
- [References](#references)
- [License](#license)
- [Author Info](#author-info)

---

## Description

Python application - Using a pipeline to evaluate multiple models and hyper parameters to help choose the best settings for this data.

- Import the dataset and ensure that it loaded properly.
- Prepare the data for modeling by performing the following steps:
- Drop the column “Load_ID.”
- Drop any rows with missing data.
- Convert the categorical features into dummy variables.
- Split the data into a training and test set, where the “Loan_Status” column is the target.
- Create a pipeline with a min-max scaler and a KNN classifier (see section 15.3 in the Machine Learning with Python 1. Cookbook).
- Fit a default KNN classifier to the data with this pipeline. Report the model accuracy on the test set. Note: Fitting a pipeline model works just like fitting a regular model.
- Create a search space for your KNN classifier where your “n_neighbors” parameter varies from 1 to 10. (see section 15.3 in the Machine Learning with Python Cookbook).
- Fit a grid search with your pipeline, search space, and 5-fold cross-validation to find the best value for the “n_neighbors” parameter.
- Find the accuracy of the grid search best model on the test set. Note: It is possible that this will not be an improvement over the default model, but likely it will be.
- Now, repeat steps 6 and 7 with the same pipeline, but expand your search space to include logistic regression and random forest models with the hyperparameter values in section 12.3 of the Machine Learning with Python Cookbook.
- What are the best model and hyperparameters found in the grid search? Find the accuracy of this model on the test set.


#### Technologies

- Python
- 

[Back To The Top](#read-me-template)

---

## How To Use

#### Installation

No special instructions here for the python file.  You'll need to update the code to point to where you've saved your product review information.

#### API Reference

```
[Back To The Top](#read-me-template)

---

## References
[Back To The Top](#read-me-template)

---

## License

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#read-me-template)

---

## Author Info

- Github - [Michael Paris - Razrbak501](https://github.com/razrbak501)
- LinkedIn - [Michael Paris](https://www.linkedin.com/in/michael-alan-paris/)

[Back To The Top](#read-me-template)
