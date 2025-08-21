# Fake News Detection

![fake news image](./assets/jorge-franganillo-34zq7tzqRSw-unsplash.jpg)
<div align="center">
  <p style="text-align: center;">
    <sup>
      <i>
        Image Source: 
        <a href="https://unsplash.com/@franganillo">Jorge Franganillo</a>
        from
        <a href="https://unsplash.com/photos/a-blue-typewriter-sitting-on-top-of-a-desk-next-to-a-tv-34zq7tzqRSw">Unsplash</a>
      </i>
    </sup>
  </p>
</div>

## Introduction

This program is a fake news detector that utilizes machine learning to analyze and classify news articles that may be either real or fake. This is achieved by analyzing the results of various machine learning models after they process input data taken from data tables. The machine learning models used within this program include Naive Bayes, Logistic Regression, Random Forest, and Support Vector Machine. 

<br/>

To support the models, TfidfVectorizer, KMeans, and RandomForestClassifier are used to present the information in a usable way for some models and for others to highlight the key features the models should consider as important features. It also uses a simple function for preprocessing the plain text data of the news articles in order to filter out unnecessary characters and to make sure the text will be accepted by the models during the training and testing phases. The two relevant files are named "fake_news.csv" and "true_news.csv".

<br/>

## Getting Started
This section details how you can get started with using the fake news detector to run it for yourself. However, there are a few required dependencies you will need in order to run the code. You will also need to download the code from Github as well as install Python, Jupyter Notebook, and the required libraries the code utilizes onto your system.

<br/>

### Dependencies
* Understanding of Basic Terminal Commands
* Installing Python, Jupyter Notebook, & Required Libraries
* Downloading the GitHub Repository

<br/>

> **Note:** If you are new to coding, or do not know how to use your system's terminal, please refer to the following resources:
> - [What is a Command Prompt?](https://www.geeksforgeeks.org/operating-systems/what-is-a-command-prompt/)
> - [Introduction to Linux Shell & Shell Scripting](https://www.geeksforgeeks.org/linux-unix/introduction-linux-shell-shell-scripting/)
> - [Linux Commands Cheat Sheet](https://www.geeksforgeeks.org/linux-unix/linux-commands-cheat-sheet/)

<br/>

### Installation

1. To install Python & Jupyter Notebook, follow the directions on their website based on your system's type, which can be found here:
   * [Python Install](https://www.python.org/downloads/)
   * [Jupyter Notebook Install](https://jupyter.org/install)
   
   <br/>

   Additionally, the following are the main required libraries in order for the code to run. In order to install, Please type the following
   commands into your terminal globally prior to running the code:
   ```sh
   pip install pandas
   ```

   ```sh
   pip install matplotlib
   ```

   ```sh
   pip install scikit-learn
   ```

<br/>

2. To clone the repository from GitHub, use your system's terminal to navigate to the location where you want this project to be located using the `cd` command in your terminal:
   ```sh
   cd ./your-desired-path-to-folder-here/
   ```
   
  <br/>
  
   Once there, run the following command:
   ```sh
   git clone https://github.com/ila-w/fake-news-detection.git
   ```
<br/>

  > **Note:** Your user navigation information will vary depending on your system and where you saved the folder when cloning it from GitHub.
  > ```text
  > Users/
  > └── username/
  >   └── Desktop/
  >       └── fake-news-detection/
  > ```

<br/>

3. Before going any further, verify that the "true-news.csv" and "fake-news.csv" files are inside the `datasets/` folder or the code will be unable to run. You can check this by navigating to the folder using your system's terminal or folder navigation program (Finder or File Explorer).
   ```text
   fake-news-detection/
   └── datasets/
       ├── fake-news.csv
       ├── true-news.csv
   ├── fake-news-detector.ipynb
   ```

<br/>


## Usage

1. In your system's terminal (Command Prompt, Powershell, Terminal), navigate to the "fake-news-detection" folder:
   ```sh
   cd ./path-to-folder-here/fake-news-detection/
   ```

2. Open the program in Jupyter Notebook by running the command:
   ```sh
   jupyter noteboook
   ```
3. Once Jupyter Notebook is running, click on "fake-news-detector.ipynb" to open the program file.

```text
fake-news-detection/
├── fake-news-detector.ipynb
```

4. At the top of the page you will see a button labeled "Run". Click the button and then select the "Run Selected Cell and All Below" option. Your program should now be running! 

> **Note**:
> If there are any additional errors, please check the console to identify the libraries your system is still missing.
> Once found, use `pip install [library name here]` to finish installing the required libraries.

<br/>


## Acknowledgements

### References

Kuntur, S., Wróblewska, A., Paprzycki, M., & Ganzha, M. (2024). "Fake News Detection: It's All in the Data!" *Cornell University arXiv*, pp. 1-12. [https://www.doi.org/10.48550/arXiv.2407.02122](https://www.doi.org/10.48550/arXiv.2407.02122).
- Github repo: [https://github.com/fakenewsresearch/](https://github.com/fakenewsresearch/)
- Kaggle dataset: [https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset](https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset)

<br/>

Lazer, D. M.J., Baum, M. A., Benkler, Y., Berinsky, A. J., Greenhill, K. M., Menczer, F., Metzger, M. J., Nyhan, B., Pennycook, G., Rothschild, D., Schudson, M., Sloman, S. A., Sunstein, C. R., Thorson, E. A., Watts, D. J., & Zittrain, J. L. (2018). "The science of fake news." <i>Science</i>, <i>359</i>(6380), pp. 1094–1096. [https://doi.org/10.1126/science.aao2998](https://doi.org/10.1126/science.aao2998).

<br/>

Hussain, F. G., Wasim, M., Hameed, S., Rehman, A., Asim, M. N., & Dengel, A. (2025). "Fake News Detection Landscape: Datasets, Data Modalities, AI Approaches, Their Challenges, and Future Perspectives." *IEEE*, *13*, pp. 54757-54778. [https://www.doi.org/10.1109/ACCESS.2025.3553909](https://www.doi.org/10.1109/ACCESS.2025.3553909).

<br/>

### Authors

Ila Wallace

<p style="text-align: center;">
    <sup>
        Contributions from Ismael Suarez, Maddie Myer, Christian Flores, and Brenden L'Heureux
    </sup>
  </p>
