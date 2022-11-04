# Mental-Heath-Disease-Detection

Keywords: Flask, Tensorflow, keras, numpy, pandas, CNN, Reddit, matplotlib, seaborn.

### Installation
1. Create a virtual environment.
```
python -m venv env
```
2. Run Environment (Activate)
```
env\Scripts\activate.bat 
```
3. Install dependencies from `requirements.txt`.
```
pip install -r requirements.txt
```

### Usage
Run the project
```
python app/main.py
```
The project should open on [127.0.0.1:8000](http://127.0.0.1:8000).
![image]()


### Approach
The Project is built to Indentify Mental health Diseases from text. <br>
The Diseases currently focused are Depression, Bipolar Disorder and Anxiety. 

###### Steps for Model Building.
1. Web scrapped 1 lakh+ real world data from reddit posts forum of Depression, Anxiety and Bipolar Disorder.
2. Lemmatization and Tokenization of Text.
3. Feature Selection: Identification of Unique tokens.
4. Spliting the Training and testing data in the ratio of 0.8: 0.2.
5. Using CNN to train the model. (Using embedding and Maxpooling).
6. Calculate the loss function using Binary Cross Entropy and Adam Optimizer for Optimization.
