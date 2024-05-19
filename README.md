# Testing_Machine_Learning_Algorithms_for_MITM_attacks

## Përshkrim

Në sigurinë kompjuterike, sulmi Man In The Middle(MITM) është një sulm kibernetik ku sulmuesi transmeton dhe ndryshon fshehurazi komunikimet midis dy palëve që besojnë se janë drejtpërdrejt duke komunikuar me njëri-tjetrin. Për më tepër, një sulmues mund të kapë, modifikojë ose shkatërrojë mesazhet për të ndërprerë komunikimin. Ndërkohë që ekzistojnë metoda si firewall-et dhe sistemet e zbulimit të ndërhyrjeve (IDS) për të parandaluar sulmet MITM, këto zakonisht zbatohen në një nivel administrativ, duke lënë sistemet e klientëve të pambrojtura. Qëllimi ynë është të zhvillojmë një sistem efektiv të zbulimit të ndërhyrjeve (IDS) duke përdorur algoritmet e MM për të zbuluar dhe parandaluar sulmet MITM në rrjet në nivelin e klientit.

## Gjuha e përdorur

Ne për këtë projeKt kemi përdorur gjuhën programuese python.

## Libraritë

Projekti përfshinë këto librari:

| Imports                                             |
|-----------------------------------------------------|
| import pandas as pd                                 |
| import numpy as np                                  |
| from sklearn.svm import OneClassSVM                 |
| from sklearn.model_selection import train_test_split|
| from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score, roc_auc_score                                         |
| from sklearn.tree import DecisionTreeClassifier     |
| from sklearn.linear_model import LogisticRegression |
| import matplotlib.pyplot as plt                     |

## Ekzekutimi

Për të ekzekutuar projektin, secili algoritëm është ndarë në file përkatës dhe për t'i ekzekutuar duhet të run secilin file veçmas. Algoritmet që kemi testuar janë:

- Decision Tree Classifier
- Support Vector Machine (SVM)
- Neural Network
- Logistic Regression

Për të ekzekutuar projektin, ndiqni këto hapa:

1. Sigurohuni që keni instaluar Python dhe libraritë e nevojshme.
2. Sigurohuni që dataset-i gjendet në folderin "Dataset" dhe titullohet "WIFIDATA.csv".
3. Ekzekutoni secilin file të algoritmeve veçmas:

- DecisionTreeClassifierMode.ipynb
- LogisticRegression.ipynb
- NeuralNetwork.ipynb
- SVM.ipynb

Për shembull, për të ekzekutuar Decision Tree Classifier, përdorni komandën:
```bash
python DecisionTreeClassifierMode.ipynb
```

## Dataset-i

Dataset-i duhet të vendoset në folderin "Dataset" dhe të titullohet "WIFIDATA.csv".

## Vërejtje

Për ekzekutimin e projektit përdorni gjithashtu Jupyter Notebook. Sigurohuni që të keni të instaluar Jupyter Notebook, ose ta përdorni atë përmes browser-it.