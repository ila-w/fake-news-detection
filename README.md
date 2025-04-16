# Fake News Detection

A program which compares the metrics between various machine learning models when used to detect fake news.

## Description

This program is a fake news detector that utilizes machine learning to analyze and classify news articles 
that may be either real or fake. This is achieved by analyzing the results of various machine learning models 
after they process input data taken from data tables. The machine learning models used within this 
program include Naive Bayes, Logistic Regression, Random Forest, and Support Vector Machine. To support the models, 
TfidfVectorizer, KMeans, and RandomForestClassifier are used to present the information in a usable way for some models 
and for others to highlight the key features the models should consider as important features. It also uses 
a simple function for preprocessing the plain text data of the news articles in order to filter out 
unnecessary characters and to make sure the text will be accepted by the models during the training 
and testing phases. The two relevant files are named "fake_news.csv" and "true_news.csv".

## Functionality

* Load and preprocesses real-world news datasets
* Train and evaluate machine learning models for fake news detection
* Use various sources (fake-news.csv, gossipcop_fake.csv, gossipcop_real.csv, and true-new.csv) to build robust classification models
* No live web deployment
* Datasets must be manually downloaded prior to running the notebooks

## Getting Started

### Dependencies

* Python 
* Jupyter Notebook

### Installation

Clone the repository from GitHub
In your local terminal, navigate to the location where you want this project to sit and then run the following commands:
*     git clone https://github.com/ila-w/fake-news-detection.git
*     cd fake-news-detection

<br/>

#### 

> **Note**:
> If you are getting errors from not having the required libraries, type the following commands into your terminal and then hit `Return↩︎`:
> ```sh
> pip install pandas
> ```
>
> ```sh
> pip install matplotlib
> ```
>
> ```sh
> pip install scikit-learn
> ```

<br/>

## Usage

### Running the program

In file explorer, navigate to the "fake-news-detection" folder, then go into the "datasets" folder.
  
Move "true-news.csv" and "fake-news.csv" from the datasets folder to its parent folder, "fake-news-detection".
  
In terminal, navigate to the fake-news-detection folder.
  
Open the program in Jupyter Notebook by running the command:

      jupyter notebook

Once in Jupyter Notebook, click on "fake-news-detection-models.ipynb" to pull up the program.
  
At the top of the page you will see a tab labeled "Run". Click this tab and then click on the "Run Selected Cell and All Below" option.
  
<br/>

Your program should now be running! If there are any errors, check the note in the Installation section of this README for help on installing the required libraries.

<br/>


## Acknowledgements

### References

Kuntur, S., Wróblewska, A., Paprzycki, M., & Ganzha, M. (2024). "Fake News Detection: It's All in the Data!" *Cornell University arXiv*, pp. 1-12. [https://www.doi.org/10.48550/arXiv.2407.02122](https://www.doi.org/10.48550/arXiv.2407.02122).
- Github repo: [https://github.com/fakenewsresearch/](https://github.com/fakenewsresearch/)
- Kaggle dataset: [https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset](https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset)

<br/>
Lazer, D. M.J., Baum, M. A., Benkler, Y., Berinsky, A. J., Greenhill, K. M., Menczer, F., Metzger, M. J., Nyhan, B., Pennycook, G., Rothschild, D., Schudson, M., Sloman, S. A., Sunstein, C. R., Thorson, E. A., Watts, D. J., & Zittrain, J. L. (2018). "The science of fake news." <i>Science</i>, <i>359</i>(6380), pp. 1094–1096. [https://doi.org/10.1126/science.aao2998](https://doi.org/10.1126/science.aao2998).

<br/> <br/>
Hussain, F. G., Wasim, M., Hameed, S., Rehman, A., Asim, M. N., & Dengel, A. (2025). "Fake News Detection Landscape: Datasets, Data Modalities, AI Approaches, Their Challenges, and Future Perspectives." *IEEE*, *13*, pp. 54757-54778. [https://www.doi.org/10.1109/ACCESS.2025.3553909](https://www.doi.org/10.1109/ACCESS.2025.3553909).

<br/>

### Authors

Ila Wallace

Contributions from Ismael Suarez, Maddie Myer, Christian Flores, and Brenden L'Heureux
