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
After installing the required libraries, you can run Jupyter Notebook to view and run the code.
The training dataset is too large to upload. if you want to use the model, you can download the training result (initial, transmission and emission probability, and pinyin states) and load them into the model.
