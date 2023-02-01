<!--
Hey, thanks for using the awesome-readme-template template.  
If you have any enhancements, then fork this project and create a pull request 
or just open an issue with the label "enhancement".

Don't forget to give this project a star for additional support ;)
Maybe you can mention me or this repo in the acknowledgements too
-->
<div align="center">

  <img src="assets/logo.png" alt="logo" width="310" height="260" />
  <h1>Income Qualification Project</h1>
  
  <p>
    A machine learning project to identify level of Income Qualification for families in South America 
  </p>
  
  
<!-- Badges -->
<div align="center">
 
<a href='https://github.com/chroline/well_app/releases'>
  
<img src='https://img.shields.io/github/v/release/chroline/well_app?color=%23FDD835&label=version&style=for-the-badge'>
  
</a>
  
<a href='https://github.com/chroline/well_app/blob/main/LICENSE'>

<img src='https://img.shields.io/github/license/chroline/well_app?style=for-the-badge'>
  
</a>
  
<a href='https://github.com/chroline/well_app/blob/main/LICENSE'>

<img src='https://img.shields.io/badge/-MIT-blue?style=for-the-badge'>
</a>
  
</div>
  
   
<h4>
    <a href="https://github.com/Louis3797/awesome-readme-template/">Project Overview</a>
  <span> · </span>
    <a href="https://github.com/Louis3797/awesome-readme-template">Documentation</a>
  <span> · </span>
    <a href="https://github.com/Louis3797/awesome-readme-template/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/Louis3797/awesome-readme-template/issues/">Request Feature</a>
  </h4>
</div>

<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Problem Statement](#star2-screenshots)
  * [Screenshots](#camera-screenshots)
  * [Tech Stack](#space_invader-tech-stack)
  * [Libraries and Tools](#clipboard-libraries)
  * [Features](#dart-features)
  * [Machine Learning](#european_castle-machine-learning)
  * [Environment Variables](#key-environment-variables)
- [Getting Started](#toolbox-getting-started)
  * [Prerequisites](#bangbang-prerequisites)
  * [Installation](#gear-installation)
  * [Running Tests](#test_tube-running-tests)
  * [Run Locally](#running-run-locally)
  * [Deployment](#triangular_flag_on_post-deployment)
- [Usage](#eyes-usage)
- [Roadmap](#compass-roadmap)
- [Contributing](#wave-contributing)
  * [Code of Conduct](#scroll-code-of-conduct)
- [FAQ](#grey_question-faq)
- [License](#warning-license)
- [Contact](#handshake-contact)
- [Acknowledgements](#gem-acknowledgements)

  

<!-- About the Project -->
## :star2: Problem Statement
Many social programs have a hard time making sure the right people are given enough aid. It's tricky when a program focuses on the poorest segment of the population. This segment of population can't provide the necessary income and expense records to prove that they qualify.
### 🧐 Proposed solution
In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. With PMT, agencies use a model that considers a family's observable household attributes like the material of their walls and ceiling or the assets found in their homes to classify them and predict their level of need. While this is an improvement, accuracy remains a problem as the regions population grows and poverty declines.

The Inter-American Development Bank (IDB) believes that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT's performance.

<!-- Screenshots -->
### :camera: EDA Plots
### Households missing Rent Payments
> ![Missing Rent Payments](https://github.com/JohnTan38/Project-Income-Qualification/blob/main/assets/Miss_RentPayment.PNG?raw=true)
<br>
 'Other' - households that missed rent payments .<br>

### Target vs Total count
> ![Target vs Total](https://github.com/JohnTan38/Project-Income-Qualification/blob/main/assets/Target_Total.PNG?raw=true)
<br>
 1 - Extreme poverty <br>
 2 - Moderate poverty <br>
 3 - Vulnerable households <br>
 4 - Non-vulnerable households <br>
<br>
<div align="center"> 
  
</div>


<!-- TechStack -->
# :space_invader: Tech Stack

<a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> 

# 📔: Libraries and Tools
<details>
  <summary>Data Manipulation</summary>
  <ul>
    <li><a href="https://pandas.pydata.org/docs//">Pandas</a></li>
    <li><a href="https://pandas.pydata.org/docs/reference/index.html#api">Pandas API Reference</a></li>
    <li><a href="https://pandas.pydata.org/docs/reference/api/pandas.crosstab.html">CrossTab</a></li>
    <li><a href="https://numpy.org/doc/stable/">NumPy</a></li>
  </ul>
</details>

<details>
  <summary>Machine Learning</summary>
  <ul>
    <li><a href="https://scikit-learn.org/stable//">SciKit Learn</a></li>
    <li><a href="https://scikit-learn.org/stable/supervised_learning.html#supervised-learning">Supervised Learning</a></li>
    <li><a href="https://scikit-learn.org/stable/model_selection.html#model-selection">Model selection & evaluation</a></li>
    <li><a href="https://scipy.org/">SciPy</a></li>
    <li><a href="https://www.statsmodels.org/stable/index.html">statsmodels</a></li>
    
  </ul>
</details>

<details>
<summary>Visualization</summary>
  <ul>
    <li><a href="https://matplotlib.org/">Matplotlib</a></li>
    <li><a href="https://seaborn.pydata.org/">Seaborn</a></li>
    
    
  </ul>
</details>



<!-- Features -->
### :dart: ML Pipeline

- EDA and Data Analysis
- Fitting the model; Hyperparameter Tuning
- Cross-validation and Model Evaluation

<!-- ML Model Reference -->
### :art: Machine Learning

| ML Tool             | Implementation                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Library | Sci-Kit Learn |
| Classifier | Random Forest Classifier |
| Hyperparameters Tuning | Grid Search CV |
| Metrics | Confusion Matrix |


<!-- Env Variables -->
### :key: Environment Libraries

To run this project, you will need to import the following to your .ipynb file

`sklearn.ensemble`

`sklearn.model.selection`
`sklearn.preprocessing`
`sklearn.pipiline`

`pandas`
`numpy`
`matplotlib.pyplot`
`seaborn`

<!-- Getting Started -->
## 	:toolbox: Getting Started

<!-- Prerequisites -->
### :bangbang: Prerequisites

This project uses Python 3.9++

```bash
 pip install -U scikit-learn
```

<!-- Installation -->
### :gear: Installation

Install my-project

```bash
  pip install pandas
  pip install numpy
  cd my-project
```
   
<!-- Running Tests -->
### :test_tube: Running Tests

To run tests, run the following command

```bash
  yarn test test
```

<!-- Run Locally -->
### :running: Run Locally

Clone the project

```bash
  git clone https://github.com/JohnTan38/project-income-qualification.git
```

Go to the project directory

```CLI
  cd my-project
```

Install libraries and dependencies

```CLI
  pip install -r requirements.txt
```

Start jupyter notebook

```bash
  C:\Users\...\AppData\Local\Programs\Python\Python311\Scripts>jupyter notebook
```


<!-- Deployment -->
### :triangular_flag_on_post: Deployment

To deploy this project run

```jupyter notebook / VS Code
  
```


<!-- Usage -->
## :eyes: Usage

Use this space to tell a little more about your project and how it can be used. Show additional screenshots, code samples, demos or link to other resources.


```Python
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import train_test_split
from sklearn.model_selection import GridSearchCV

X_train,X_test,Y_train,Y_test=train_test_split(X_data_1,Y_data,test_size=0.25,stratify=Y_data,random_state=10)

rfc=RandomForestClassifier(random_state=10)

RFC=best_.best_estimator_
Model=RFC.fit(X_train,Y_train)
pred=Model.predict(X_test)
```

### 🧐 Bias in machine learning datasets
When collecting data to build a training set for Machine Learning solutions, it is important to understand the breadth and depth of the data available to you.
In the Duke-Margolis research, they call out that “...there are geographic biases to much of the data used to train AI. If the tools being built are deployed in more rural or varied regional populations, the representation of the data may not overlay in the same way and can lead to unexpected outcomes based on the machine learning biased data sets.
The population structure of the source data can be also weighted based on who is included or excluded.

Missing Feature Values
If your data set has one or more features that have missing values for a large number of examples, that could be an indicator that certain key characteristics of your data set are under-represented.

### ✅:gem: Some suggestions to address bias
Question the preconceptions: A machine learning model learns from historical decisions and their intent, where the intent is known. At every stage of training data preparation, it is important to question where the data is coming from, whose perceptions affected earlier decisions, and what changes need to be made in the data accordingly to clean it for training purposes.

Continuous development / testing:
An algorithm that works for one set of data will not likely work with an extended version of the same data. It might if we keep testing the system with challenger models and verify its predictive accuracy, transparency, and improvement rate.

<!-- Roadmap -->
## :compass: Roadmap

* [x] To conduct further research in Proxy Means Testing using multivariate regression to correlate proxies such as assets and household characteristics with poverty and income
* [ ] 


<!-- Contributing -->
## :wave: Contributing

<a href="https://github.com/Louis3797/awesome-readme-template/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Louis3797/awesome-readme-template" />
</a>




# Contributors ✨
# Contributing
<br>
Contributions are always welcome!
This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

<h3 align="left">Support:</h3>
<p><a href="https://www.buymeacoffee.com/vieming8"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="buymeacoffeeJohnTan" /></a></p><br><br>


<br>
<a href="https://www.buymeacoffee.com/vieming8" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee" height="50" width="210"></a>


<!-- Code of Conduct -->
### :scroll: Code of Conduct

Please read the [Code of Conduct](https://github.com/JohnTan38/Project-Income-Qualification/blob/add-code-of-conduct-1/CODE_OF_CONDUCT.md)

<!-- FAQ -->
## :grey_question: FAQ

- Question 1

  + Answer 1

- Question 2

  + Answer 2


<!-- License -->
## :warning: License

Distributed under the MIT License. See LICENSE.txt for more information.


<!-- Contact -->
## :handshake: Contact

Email ✉️ - vieming@gmail.com

Project Link 🌐 [https://github.com/JohnTan38/project-income-qualification.git](https://github.com/JohnTan38/project-income-qualification.git)


<!-- Acknowledgments -->
## :gem: Acknowledgements

Useful resources and libraries in project.

 - [Shields.io](https://shields.io/)
 - [https://olc.worldbank.org/sites/default/files/1.pdf](https://olc.worldbank.org/sites/default/files/1.pdf)
 - [https://sohs.alnap.org/system/files/content/resource/files/main/targeting-poorest.pdf](https://sohs.alnap.org/system/files/content/resource/files/main/targeting-poorest.pdf)
 - [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md#travel--places)
 - [Readme Template](https://github.com/othneildrew/Best-README-Template)

