# Heart-Disease-Prediction
Heart Disease Prediction
<!-- Improved compatibility of back to top link: See: https://github.com/ClassicCollins/heart-disease-prediction/back2top -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out heart-disease-prediction project. 
*** Thanks for checking out my project!
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for stars-url, forks-url, etc.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links 
-->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![MIT License][license-shield]][license-url]
[![Python][Python-logo]][Python-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Twitter][twitter-shield]][twitter-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ClassicCollins/heart-disease-prediction/blob/classic/image/logo.png">
    <img src="image/logo.png" alt="Logo" width="600" height="200">
  </a>

<h3 align="center">Heart Disease Prediction Model</h3>

  <p align="center">
    A project designed to spark your interest in heart disease prediction using Python.!
    <br />
    <a href="https://github.com/ClassicCollins/heart-disease-prediction"><strong>Explore the Model »</strong></a>
    <br />
    <br />
    <a href="https://zindi.africa/competitions/microsoft-x-data-science-nigeria-2024-ai-bootcamp-qualification-hackathon">Participate in The Project</a>
    ·
    <a href="https://github.com/ClassicCollins/heart-disease-prediction/blob/classic/.github/ISSUE_TEMPLATE/bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/ClassicCollins/heart-disease-prediction/blob/classic/.github/ISSUE_TEMPLATE/feature-request-form---.md">Request Feature</a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>View Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#project-Goal">Project Goal</a></li>
        <li><a href="#tools-and-libraries">Tools and Libraries</a></li>
        <li><a href="#steps-and-method">Steps and Method</a></li>
        <li><a href="#results">Results</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#Required-Packages">Required Packages</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://zindi.africa/competitions/microsoft-x-data-science-nigeria-2024-ai-bootcamp-qualification-hackathon)

* `Welcome` to the Heart Disease Prediction Model repository! This project was developed for the Zindi competition organized by Data Science Nigeria in partnership with Microsoft.
* `Introduction:` Heart disease is a leading cause of death worldwide, and early prediction can save lives. This project aims to build a predictive model to identify individuals at risk of heart disease using various health metrics. The model leverages machine learning algorithms to provide accurate predictions and assist healthcare professionals in making informed decisions.

### Project Goal
`The goal` of this competition is to help predict the likelihood of heart disease in Nigerian patients using machine learning techniques.
Sounds interesting right? :smile:

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Tools and Libraries

* [![Python][Python-logo]][Python-url]
* [![Pandas][Pandas-logo]][Pandas-url]
* [![NumPy][NumPy-logo]][NumPy-url]
* [![Matplotlib][Matplotlib-logo]][Matplotlib-url]
* [![Seaborn][Seaborn-logo]][Seaborn-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- STEPS and METHODOLOGY -->
## Steps and Method
* `The dataset` used for this project includes various health indicators such as
- Id/id: Identifier of the individual.
- Age: Age of the individual.
- Sex: Gender (0 = female, 1 = male).
- cp: Chest pain type (categorical).
- trestbps: Resting blood pressure.
- chol: Serum cholesterol in mg/dl.
- fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false).
- restecg: Resting electrocardiographic results (categorical).
- thalach: Maximum heart rate achieved.
- exang: Exercise induced angina (1 = yes, 0 = no).
- oldpeak: ST depression induced by exercise relative to rest.
- slope: Slope of the peak exercise ST segment.
- ca: Number of major vessels (0-4) colored by fluoroscopy.
- thal: Thalassemia (categorical).
- target (train only): Presence of heart disease (0 = no, 1 = yes).
* The data was provided by the competition organizers.
* `Data cleaning, preprocessing, and validation` were performed to ensure there were no duplicates or missing values, and that the data was in    the correct format.
* `Exploratory Data Analysis` was conducted on the dataset to visualize it and identify patterns, trends, correlations, and outliers
* `The model` was built using several machine learning algorithms, including XGBoost, SVM, Decision trees, and Random forests. 
* `Feature engineering and hyperparameter tuning` were performed to optimize the model’s performance.
* `Evaluation` The model was evaluated using accuracy metric, however, other metrics like precision, recall, and F1-score were used to evaluate the model.
* `Cross-validation` was also used to ensure the model’s robustness and generalizability.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- RESULTS -->
## Results
* XGBoost demonstrated superior accuracy compared to other models, but it likely overfitted the data.
* The SVM Classifier achieved the highest leaderboard score, followed by Random Forest, and was ultimately submitted.
* I forgot to uncheck the low score from Random Forest, which negatively impacted my leaderboard ranking.
* This was one of the key lessons I learned from the hackathon.
* Fortunately, DSN reviewed our codes and I was selected as one of the top candidate to attend `2024 Bootcamp` and contribute to Development of AI in Africa
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Install Required Packages

Ensure you have Python installed and then run:
* requirement
  ```sh
  pip install -r requirements.txt
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ClassicCollins/heart-disease-prediction.git
   ```
   ```sh
   cd heart-disease-prediction
   ```
2. Install required packages
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Notebook: Open the notebook in Jupyter and run the cells to reproduce the analysis:
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENCE -->
## License
* `MIT` License applies.
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Collins Emezie Ugwuozor - [@ClassicCollins2](https://x.com/ClassicCollins2) - ugwuozorcollinsemezie@gmail.com

Project Link: [Heart_Disease_Prediction_Project](https://www.datascienceportfol.io/collinsugwuozor/projects/6)

Don't forget to give the project a star! Thanks again!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [DSN](https://datasciencenigeria.org/ai-community-membership/)
* [Microsoft_Nigeria](https://www.microsoft.com/en-ng/contact.aspx)
* [Zindi](https://zindi.africa/)
* [Python](https://www.python.org)
* [Img Shields](https://shields.io)
* [othneildrew](https://github.com/othneildrew/Best-README-Template)
* [Google Colab](https://colab.research.google.com/)
* [MIT License](https://opensource.org/license/mit)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ClassicCollins/heart-disease-prediction.svg?style=for-the-badge
[contributors-url]: https://github.com/ClassicCollins/heart-disease-prediction/contributors
[twitter-shield]: https://img.shields.io/badge/-Twitter-black.svg?style=for-the-badge&logo=x&colorB=555
[twitter-url]: https://x.com/ClassicCollins2
[traffic-shield]: https://img.shields.io/github/traffic/ClassicCollins/heart-disease-prediction.svg?style=for-the-badge
[traffic-url]: https://github.com/ClassicCollins/heart-disease-prediction/traffic
[forks-shield]: https://img.shields.io/github/forks/ClassicCollins/heart-disease-prediction.svg?style=for-the-badge
[forks-url]: https://github.com/ClassicCollins/heart-disease-prediction/forks
[stars-shield]: https://img.shields.io/github/stars/ClassicCollins/heart-disease-prediction.svg?style=for-the-badge
[stars-url]: https://github.com/ClassicCollins/heart-disease-prediction/stargazers
[issues-shield]: https://img.shields.io/github/issues/ClassicCollins/heart-disease-prediction.svg?style=for-the-badge
[issues-url]: https://github.com/ClassicCollins/heart-disease-prediction/issues
[license-shield]: https://img.shields.io/github/license/ClassicCollins/heart-disease-prediction.svg?style=for-the-badge
[license-url]: https://github.com/ClassicCollins/heart-disease-prediction/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-white.svg?style=for-the-badge&logo=linkedin&colorB=blue
[linkedin-url]: https://linkedin.com/in/collins-ugwuozor
[product-screenshot]: image/screenshot1.png
[Python-logo]: https://img.shields.io/badge/Python-20232A?style=for-the-badge&logo=python&logoColor=61DAFB
[Python-url]: https://www.python.org/
[Pandas-logo]: https://img.shields.io/badge/Pandas-20232A?style=for-the-badge&logo=pandas&logoColor=blue
[Pandas-url]: https://pandas.pydata.org/
[NumPy-logo]: https://img.shields.io/badge/Numppy-20232A?style=for-the-badge&logo=numpy&logoColor=61DAFB
[NumPy-url]: https://numpy.org/
[Matplotlib-logo]: https://img.shields.io/badge/Matplotlib-red?style=for-the-badge&logo=matplotlib&logoColor=0769AD
[Matplotlib-url]: https://matplotlib.org/ 
[Seaborn-logo]: https://img.shields.io/badge/Seaborn-20232A?style=for-the-badge&logo=seaborn&logoColor=61DAFB
[Seaborn-url]: https://seaborn.pydata.org/
