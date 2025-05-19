# Spam Email Detection 🔥📧

Detect spam emails using a neural network (TensorFlow + Keras). Built in Jupyter Notebook.

## 🔧 stack

- Python
- TensorFlow / Keras
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## 📁 files

.
├── Spam_Email_Neural_Network.ipynb   # main notebook  
└── dataset.csv                        # email data (ham/spam)

## 🚀 usage

$ git clone https://github.com/Tareqhasanmunna/Spam-Email-Detection-using-Neural-Networks  
$ cd spam-email-detector-using-Neural-Network  

# (optional) create virtual env
$ python -m venv venv  
$ source venv/bin/activate  # or venv\Scripts\activate on Windows  

# install deps
$ pip install -r requirements.txt  

# run
$ jupyter notebook Spam_Email_Neural_Network.ipynb  

## 🧠 model

- Embedding → Dense → Dropout → Output (Sigmoid)
- Loss: binary_crossentropy
- Optimizer: adam
- Metrics: accuracy

## 📊 output

- accuracy/loss graphs  
- confusion matrix  

## ✅ todo

[ ] add GUI  
[ ] save/load model  
[ ] Streamlit/Flask web version  

## 👤 author
Tareq Hasan Munna
