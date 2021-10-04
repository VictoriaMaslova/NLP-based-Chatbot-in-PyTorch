# NLP based Chatbot in PyTorch
<img src="https://miro.medium.com/max/1400/1*VqLvWcTKgVpv1idxII591A.jpeg" width="470" height="350">


## Simple chatbot implementation with PyTorch.

* The implementation should be easy to follow for beginners and provide a basic understanding of chatbots.

* The implementation is straightforward with a Feed Forward Neural net with 2 hidden layers.

* Customization for your own use case is super easy. Just modify intents.json with possible patterns and responses and re-run the training (see below for more info).

In [this article](https://medium.com/@mlvictoriamaslova/nlp-based-chatbot-in-pytorch-bonus-flask-and-javascript-deployment-474c4e59ceff) on Medium I explain some NLP concepts that underlies building Chatbots.

---


## Installation

### Create an environment

Whatever you prefer (e.g. conda or venv)

```
mkdir myproject
$ cd myproject
$ python3 -m venv venv
```

### Activate it

Mac / Linux:
```
. venv/bin/activate
```
Windows:

```
venv\Scripts\activate
```

### Install PyTorch and dependencies

For Installation of PyTorch see official website.

You also need nltk:
```
pip install nltk
```
If you get an error during the first run, you also need to install nltk.tokenize.punkt: Run this once in your terminal:

```
$ python
>>> import nltk
>>> nltk.download('punkt')
```

### Usage

Run
```
python train.py
```
This will dump data.pth file. And then run
```
python chat.py
```
