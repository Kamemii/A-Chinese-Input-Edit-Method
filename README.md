# A-Chinese-Input-Edit-Method

## Introduction
This is the final project for 24 Spring NLP in UPF. In this project I trained a model based on HMM to convert pinyin into Chinese characters. 

## Instructions
### 1. Dependencies
To implement this work, you need to execute the following command block in the terminal. <br>
```Bash
# install libraries for model training
pip install tqdm == 4.66.2

# install libraries for data processing
pip install pypinyin == 0.50.0

# install libraries for data visualization
pip install matplotlib == 3.8.1
pip install seaborn==0.13.2
```
### 2. Viewing and running the code
After installing the required libraries, you can run Jupyter Notebook to view and run the code.<br>

The training dataset is too large to upload on Github. If you need it, you can download from: https://drive.google.com/file/d/1-_JIgT0ifndIFzgGszDsGraR1p9o2IY3/view?usp=sharing <br>

If you just want to use the model, you can download the parameters for HMM (initial, transmission and emission probability, and pinyin states) and load them into the model.
