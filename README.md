# Applied Deep Learning Class

## Uniandes - Summer 2018

The use of statistical models in computer algorithms allows computers to make decisions and predictions, and to perform tasks that traditionally require human cognitive abilities. Deep learning is the interdisciplinary field at the intersection of statistics and computer science which develops such algorithnms and interweaves them with computer systems. It underpins many modern technologies, such as speech recognition, internet search, bioinformatics, computer vision, Amazon’s recommender system, Google’s driverless car and the most recent imaging systems for cancer diagnosis are all based on Deep Learning technology.

This course on Deep Learning will explain how to build systems that learn and adapt using real-world applications. Some of the topics to be covered include deep learning frameworks, convolutional neural networks, generative models nadrecurrent models. The course will be project-oriented, with emphasis placed on writing software implementations of learning algorithms applied to real-world problems, in particular, image analysis, image captioning, natural language pocessing, sentiment detection, among others.

Instructors: 
- Dr. Alejandro Correa Bahnsen <http://albahnsen.com>
- Prof. Dr. Fabio Gonzalez <http://dis.unal.edu.co/~fgonza/>

Graduate assistant:
- Sergio Angulo <sa.angulo@uniandes.edu.co>

## Resources

* \[Goodfellow16\] Goodfellow, I., Bengio, Y., Courville, A., & Bengio, Y. (2016). [Deep learning](http://www.deeplearningbook.org/) (Vol. 1). Cambridge: MIT press.
* Fabio González, [Machine Learning](https://fagonzalezo.github.io/ml-2018-1/), 2018-1, Universidad Nacional de Colombia
* Fabio González, [Deep Learning for Text Analysis and Understanding](https://fagonzalezo.github.io/dl-tau-2017-2/) , Fall 2017, University of Houston
* Fabio González, [Representation Learning and Deep Learning Tutorial](https://fagonzalezo.github.io/dl_tutorial_upv/), 2016, Univ. Politécnica de Valencia


## Schedule

### Introduction to Machine Learning and Neural Networks
| Date | Session         | Notebooks/Presentations          | Exercises |
| :----| :----| :------------- | :------------- | 
| June-6 | Introduction to python and ML | <ul><li>[1 - Intro to ML](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/01-IntroMachineLearning.ipynb) </li> <li>[2 - Intro to Python for data analysis](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/02-IntroPython_Numpy_Scypy_Pandas.ipynb) </li><li> [3 - Linear Regression](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/03-linear_regression.ipynb) </li><li>[4 - Logistic Regression](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/04-logistic_regression.ipynb)</li></ul> | <ul><li>[E1 - Python&Pandas](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/E01-Python%26Numpy%26Pandas.ipynb) </li> <li> [E2 - Regression](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/E02-Regression-IncomePrediction.ipynb) </li></ul> | 
| June-8 | Machine learning systems | <ul><li>[5 - Data preparation and model evaluation](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/05-data_preparation_evaluation.ipynb)</li><li>[6 - Sampling](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/06_Unbalanced_Datasets.ipynb)</li><li>[7 - Ensemble methods](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/07_EnsembleMethods.ipynb)</li><li>[8 - Model deployment](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/08_Model_Deployment.ipynb)</li></ul> | <ul><li>[E3 - Cross Validation](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/E03-CrossVal-CreditScoring.ipynb) </li> <li>[E4 - Sampling and Ensembles](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/E04-Sampling-RF-FraudDetection.ipynb)</li><li> **Project1 - Kaggle** </li></ul> | 
| June-20 | Neural networks basics | <ul><li>[9 - Intro to NN](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/09-Intro_Neural_Networks.ipynb) </li> <li>[10 - Perceptron Training](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/10-Perceptron_Training.ipynb) </li><li> [11 - NN in Keras](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/11-NN_in_Keras.ipynb) </li></ul> | <ul><li>[E5 - Neural Networks](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/E05-neural%20networks.ipynb) </li> </ul> | 

### Introduction to Deep Learning
| Date | Session         |Notebooks/Presentations          | Exercises |
| :----| :----| :------------- | :------------- | 
| June-22 | Introduction to deep learning and applications |<ul><li> [12 - Intro to Deep Learning](https://github.com/albahnsen/AppliedDeepLearningClass/blob/master/presentations/DL-introduction.pdf) </li> </ul>  |   | 
| July-4 | Deep learning frameworks |<ul><li>[13 - Intro to TensorFlow](https://github.com/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/13-IntroTensorFlow.ipynb) </li><li>[14 - Deep Learning Frameworks](https://fagonzalezo.github.io/dl-tau-2017-2/lecture4_slides.pdf) </li></ul>  |<ul><li>[E6 - TensorFlow and Keras](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/E06-TensorFlow-Keras.ipynb) </li> </ul>  | 

### Deep Learning for Image Analysis
| Date | Session         | Notebook          | Exercises |
| :----| :----| :------------- | :------------- | 
| July-5 | Deep learning for image analyssis & CNN | <ul><li> [15 - CNN training in Keras](https://colab.research.google.com/drive/1Z6r82FlQTBXTh3GZCPc9LeZClxFVhcl_) </li> </ul>  | <ul><li>[P2 - Image Classification with CNN](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/P2-ImageClassificationCNN.ipynb) </li> </ul> | 
| July-6 | CNN and transfer learning | <ul><li>[16 - Convolutional Neural Networks](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/16-CNN.ipynb) </li> <li>[17 - Transfer Learning](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/17-Transfer%20Learning.ipynb) </li></ul>  | <ul><li>[E7 - Image Captioning](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/E07-CNN_TransferLearning_CIFAR10.ipynb) </li> </ul> | 
| July-11 | Generative models | <ul><li>[16 - Convolutional Neural Networks](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/16-CNN.ipynb) </li> <li>[18 - Generative Adversarial Networks](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/18-GenerativeAdversarialNetworks.ipynb) </li></ul>  |  | 

### Deep Learning for Text Analysis
| Date | Session         | Notebook          | Exercises |
| :----| :----| :------------- | :------------- | 
| July-12 | Intro to NLP & Intro to RNN | <ul><li> [19 - Intro to Natural Language Processing](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/notebooks/19-NLP.ipynb) </li> </ul> | <ul><li>[E8 - Sentiment Classification](http://nbviewer.jupyter.org/github/albahnsen/AppliedDeepLearningClass/blob/master/exercises/E08-SentimentPrediction.ipynb) </li> </ul> | 
| July-13 | Word2vec & RNN for text analysis |  |  | 

### Deep Learning for Applications
| Date | Session         | 
| :----| :----| 
| July-16 | Deep learning applications |  
| July-17 | Deep learning applications |  
| July-19 | Deep learning applications |  

### Final Project
| Date | Session         | 
| :----| :----| 
| July-23 | Final project presentations | 


