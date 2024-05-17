# Testing_Machine_Learning_Algorithms_for_MITM_attacks

##Pershkrim

Në sigurinë kompjuterike, sulmi Man In The Middle(MITM) është një sulm kibernetik ku sulmuesi transmeton dhe ndryshon fshehurazi komunikimet midis dy palëve që besojnë se janë drejtpërdrejt duke komunikuar me njëri-tjetrin. Për më tepër, një sulmues mund të kapë, modifikojë ose shkatërrojë mesazhet për të ndërprerë komunikimin. Ndërkohë që ekzistojnë metoda si firewall-et dhe sistemet e zbulimit të ndërhyrjeve (IDS) për të parandaluar sulmet MITM, këto zakonisht zbatohen në një nivel administrativ, duke lënë sistemet e klientëve të pambrojtura. Qëllimi ynë është të zhvillojmë një sistem efektiv të zbulimit të ndërhyrjeve (IDS) duke përdorur algoritmet e MM për të zbuluar dhe parandaluar sulmet MITM në rrjet në nivelin e klientit.

##Gjuha e përdorur

Ne për këtë projeKt kemi përdorur gjuhën programuese python.

##Libraritë

Projekti përfshinë këto librarI:

import pandas as pd
from sklearn import svm
import numpy as np
from sklearn.svm import OneClassSVM
from sklearn.model_selection import train_test_split  

##Ekzekutimi

Fillimisht për të ekzekutuar projektin ju duhet të keni të instaluar Jupyter Notebook, ose ta përdorni atë përmes browser-it. File-in që duhet ta ekzekutoni titullohet "Model.ipynb", mirëpo në mënyrë që ekzekutimi të funksionoj me sukses, ju duhet të siguroheni që dataset-i gjendet në folderin "Dataset" dhe titullohet "WIFIDATA.csv".
