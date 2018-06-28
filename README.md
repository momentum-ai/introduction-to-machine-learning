# Machine Learning & Artificial Intelligence Summer-Workshop
<img src="https://i.imgur.com/7ndJudh.png" style="width: 100%;">

## Presentation
https://docs.google.com/presentation/d/1mffIyYIr4G2EdrSV-uk57RmhaU3_QTQ_KLBzncQ9I0E/edit?usp=sharing

## Workshop
You can run keras (an interface to tensorflow) directly in the browser without installing the python libraries on your machine using Googles Collaboratory tool.

Do it by:
- Open a notebook
- Click "Open in playground" to get your own copy 
- Accept that it is not created by Google

Then read the code, ask for help when it is unclear what is happening(!), and run one cell at a time. Make sure not to miss any cell, and just start over from the top if anything is not working.

### Notebooks:

1. [MNIST](https://colab.research.google.com/drive/1CQNqdLp4sMOCyGiCgZic57D42xbjRf9y#scrollTo=cttxuQgZjtJl) (recognizing images of digits)
2. [Text Generation](https://colab.research.google.com/drive/1v8kVoM_Gn_E7LlykZLqYrtc8U-eY7Nt_) (learning to generate the same text as Nietzche would have written)
3. [Neural Network based Calculator](https://colab.research.google.com/drive/1zA-B4QszWnmaqtRd3PE9XBoFCdX47kUq#scrollTo=1Wkt7b8rzTI0) (learning addition of numbers by example)



### Find your own data
After looking at some examples you can modify the networks or start using keras to play with your own data. For example by downloading data from https://github.com/awesomedata/awesome-public-datasets

## More notebooks:

### Neural style transfer
<img src="https://raw.githubusercontent.com/titu1994/Neural-Style-Transfer/master/images/inputs/style/metals/burnt_gold.jpg" style="width: 100%;">

### ML / Deep Learning lecture

# Installations for working with deep learning

<img src="https://i.imgur.com/NOPJO6B.png" style="width: 100%;">

Programmet `conda` (som installeras genom miniconda) är till för att hantera olika versioner av python och python-moduler.

## Linux/OS X

1. **Install Miniconda:** https://conda.io/miniconda.html

2. **Update permissions:**
  
  ```
  $ chmod 777 ./Miniconda3-latest-MacOSX-x86_64.sh
  ```

3. **Install using bash:**
  
  ```
  $ ./Miniconda3-latest-MacOSX-x86_64.sh
  ```

## Windows

1. **Install bash. Easies via git bash:** https://git-scm.com/download/win
2. **Install Miniconda:** https://conda.io/miniconda.html
3. **Extra:** When installing tensorflow, you might need to follow: https://www.tensorflow.org/install/install_windows

## Set up python and install dependecies

1. **Create a new environment:** (Where the environment name is “ml” and the python version is 3.6.)
  
  ```
  $ conda create -n ml python=3.6
  ```

2. **Activate your environment:**
  
  ```
  $ source activate ml
  ```

3. Install packages
  
  ```
  $ pip install tensorflow keras jupyter
  ```
  
4. Start notebook

  ```
  $ jupyter notebook
  ```

  <img src="https://i.imgur.com/BEWN0fU.png" style="width: 100%;">


Python version 2 eller version 3
https://www.python.org/downloads/
Jupyter notebooks
Länk till information om installation
http://jupyter.org/install
Tensorflow
https://www.tensorflow.org/install/
Keras
https://keras.io/#installation


## Learning resources
### Google Machine Learning Crash Course
https://developers.google.com/machine-learning/crash-course/ml-intro
### Kaggle
http://kaggle.com/
### Youtube
#### 3Blue1Brown (Math)
https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw
#### Siraj Raval (Machine learning introductions)
https://www.youtube.com/channel/UCWN3xxRkmTPmbKwht9FuE5A
