### customers for marketing segmentation

## Table of CONTENTS 
---------------------
 * [Aim](#aim)
 * [Dataset used](#data)
 * [Exploring the Data](#viz)
   - [Matplotlib](#matplotlib)
   - [Seaborn](#seaborn)
 * [Predicion_with_various_model](#Predicion_with_various_model)
 * [Conclusion](#conclusion)
 

## AIM:<a name="aim"></a>

Create a model to predict whether or not a customer will Churn.

## Dataset Used:<a name="data"></a>

Dataset can be found at repository

## Exploring the Data:<a name="viz"></a>

I had use pandas and seaborn visualization skills.

**Matplotlib:**<a name="matplotlib"></a>
--------
Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the Jupyter notebook, web application servers, and four graphical user interface toolkits.You can draw up all sorts of charts(such as Bar Graph, Pie Chart, Box Plot, Histogram. Subplots ,Scatter Plot and many more) and visualization using matplotlib.

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install matplotlib:

     pip: pip install matplotlib

     anaconda: conda install matplotlib
     
     import matplotlib.pyplot as plt

for more information you can refer to [matplotlib](https://matplotlib.org/) official site

![matplotlib](https://eli.thegreenplace.net/images/2016/animline.gif)

**Seaborn:**<a name="seaborn"></a>
------
Seaborn is built on top of Python’s core visualization library Matplotlib. Seaborn comes with some very important features that make it easy to use. Some of these features are:

**Visualizing univariate and bivariate data.**

**Fitting and visualizing linear regression models.**

**Plotting statistical time series data.**

**Seaborn works well with NumPy and Pandas data structures**

**Built-in themes for styling Matplotlib graphics**

**The knowledge of Matplotlib is recommended to tweak Seaborn’s default plots.**

Environment Setup==
If you have Python and Anaconda installed on your computer, you can use any of the methods below to install seaborn:

    pip: "pip install seaborn"*

    anaconda: " conda install seaborn"*
    import seaborn as sns
    
for more information you can refer to [seaborn](https://seaborn.pydata.org/) official site.

![seaborn](https://i.stack.imgur.com/uzyHd.gif)

## Predicion with various models:<a name="Predicion_with_various_model"></a>

I have used 3 different tree based methods: A Single Decision Tree, Random Forest, AdaBoost.

**DecisionTree**

                  precision  recall   f1-score   support

          No       0.87      0.89      0.88       557
         Yes       0.55      0.49      0.52       147

     accuracy                           0.81      704
     
![18](https://user-images.githubusercontent.com/86251750/145683689-5d025bbe-1ae1-4845-bfc3-92c70243a4ea.PNG)

![19](https://user-images.githubusercontent.com/86251750/145683710-035a3313-e3bb-47a7-a60b-d74c9d951ced.PNG)

**RandomForest**

                precision    recall  f1-score   support

          No       0.85      0.87      0.86       557
         Yes       0.46      0.43      0.44       147

    accuracy                           0.77       704
    
![20](https://user-images.githubusercontent.com/86251750/145683792-a6fd605e-7df7-43c7-bc75-ef847d839ea3.PNG)

**AdaBoost**

                 precision    recall  f1-score   support

          No       0.88      0.90      0.89       557
         Yes       0.60      0.54      0.57       147

    accuracy                           0.83       704

**CONCLUSION**:<a name="conclusion"></a>

From above three model we can see that AdaBoost performs best but there are many model which we can use and further we can do hyperparameter tuning using various method like
optuna, gridsearch, hyperpot and many more to increase the accuracy of the model.

    Note-->If there is issue with opening the .ipynb file you can follow this link(https://nbviewer.org/github/pradeepsuyal/Telco-customerchurn/blob/main/Telco%20customer%20churn.ipynb)

***language used***
--------------------------
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

**Tools**
-----------------------
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)    ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)   ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![Made with matplotlib](https://user-images.githubusercontent.com/86251750/132984208-76ce70c7-816d-4f72-9c9f-90073a70310f.png)  ![seaborn](https://user-images.githubusercontent.com/86251750/132984253-32c04192-989f-4ebd-8c46-8ad1a194a492.png)

