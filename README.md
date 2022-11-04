# Mental-Heath-Disease-Detection

Keywords: Tensorflow, keras, numpy, pandas, CNN, Reddit, matplotlib, seaborn , Jupyter Notebook.

## Installation
1. Clone this Repository
```
git clone https://github.com/ankita2002/Mental-Heath-Disease-Detection.git
```
2. Open Jupyter Notebook and Run the files or Directly use the pickle files.

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
