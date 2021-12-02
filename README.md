# PySDG
<h1 align="center"><project-name></h1>

<p align="center"><project-description></p>

## Descrption:
  - PySDG is a tkinter wrapper for the Support Vector Machine(SVM) based Machine Learning Model. 
  - The SVM model has the accuracy of 86%. The training of the modele is available in the ModelTrainng.ipynb.
  - Pickle file is generated from the train model and used in the Tkinter based code,PySDG.py
  - It uses multiprocessing model to speed up the classifing
  - The code can either take a txt,pdf as input and generate the output
  - The code also take path of the directory as input and analyse the text and pdf files and generate output in the csv format
  - It could only classify the 15 out of 17 goals
  
  
## Python Modules Used:

- sklearn
- nltk
- tkinter
- multiprocessing

## Dependencies


 - pip install pip install pdfminer

 -  pip install nltk

 - pip install pickle
 
 - import nltk

 - nltk.download('stopwords')

 - nltk.download('punkt')

 - nltk.download('averaged_perceptron_tagger')

## Links

- [UN SDG](https://sdgs.un.org/goals)

- [OSDG Github Repo](https://github.com/osdg-ai)

- [Sklearn -SVM](https://scikit-learn.org/stable/modules/svm.html)

- [Dataset](https://zenodo.org/record/5550238/files/osdg-community-dataset-v21-09-30.csv?download=1)


## Screenshots

![](/screenshots/1.png)

![](/screenshots/2.png)

![](/screenshots/3.png)


## 🤝 Support

Contributions, issues, and feature requests are welcome!

