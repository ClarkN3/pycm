<div align="center">
<img src="Otherfiles/logo.png" width=250px height=250px>
<br/>
<a href="https://www.python.org/"><img src="https://img.shields.io/badge/built%20with-Python3-green.svg" alt="built with Python3" /></a>

</div>

----------

## Overview	
In the field of machine learning and specifically the problem of statistical classification, a confusion matrix, also known as an error matrix, is a specific table layout that allows visualization of the performance of an algorithm, typically a supervised learning one (in unsupervised learning it is usually called a matching matrix). Each row of the matrix represents the instances in a predicted class while each column represents the instances in an actual class (or vice versa)		
pycm(python confusion matrix) is a multi class confusion matrix library in python.

## Installation		

### Source Code
- Download [Version 0.1](https://github.com/sepandhaghighi/pycm/archive/v0.1.zip) or [Latest Source ](https://github.com/sepandhaghighi/pycm/archive/master.zip)
- Run `pip install -r requirements.txt` or `pip3 install -r requirements.txt` (Need root access)
- Run `python3 setup.py install` or `python setup.py install` (Need root access)				

### PyPI


- Check [Python Packaging User Guide](https://packaging.python.org/installing/)     
- Run `pip install pycm` or `pip3 install pycm` (Need root access)

## Usage

```python
>>> from pycm import *
>>> y_actu = [2, 0, 2, 2, 0, 1, 1, 2, 2, 0, 1, 2]
>>> y_pred = [0, 0, 2, 1, 0, 2, 1, 0, 2, 0, 2, 2]
>>> cm = ConfusionMatrix(y_actu, y_pred)
>>> print(cm)
Predict          0    1    2    
Actual
0                3    0    0    
1                0    1    2    
2                2    1    3    




Classes                                                          0                       1                       2                       
ACC(accuracy)                                                    0.83333                 0.75                    0.58333                 
BM(Informedness or Bookmaker Informedness)                       0.77778                 0.22222                 0.16667                 
DOR(Diagnostic odds ratio)                                       None                    4.0                     2.00003                 
F1(F1 Score - harmonic mean of precision and sensitivity)        0.75                    0.4                     0.54545                 
FDR(false discovery rate)                                        0.4                     0.5                     0.4                     
FN(false negative/miss/Type II error)                            0                       2                       3                       
FNR(miss rate or false negative rate)                            0.0                     0.66667                 0.5                     
FOR(false omission rate)                                         0.0                     0.2                     0.42857                 
FP(false positive/Type I error/false alarm)                      2                       1                       2                       
FPR(fall-out or false positive rate)                             0.22222                 0.11111                 0.33333                 
LR+(Positive likelihood ratio)                                   4.50005                 3.0                     1.50002                 
LR-(Negative likelihood ratio)                                   0.0                     0.75                    0.75                    
MCC(Matthews correlation coefficient)                            0.68313                 0.2582                  0.16903                 
MK(Markedness)                                                   0.6                     0.3                     0.17143                 
NPV(negative predictive value)                                   1.0                     0.8                     0.57143                 
PPV(precision or positive predictive value)                      0.6                     0.5                     0.6                     
TN(true negative/correct rejection)                              7                       8                       4                       
TNR(specificity or true negative rate)                           0.77778                 0.88889                 0.66667                 
TP(true positive/hit)                                            3                       1                       3                       
TPR(sensitivity, recall, hit rate, or true positive rate)        1.0                     0.33333                 0.5 

```
				

For more information visit [here](Document.ipynb "Document")

## Issues & Bug Reports			

Just fill an issue and describe it. We'll check it ASAP!							
or send an email to [sepand@qpage.ir](mailto:sepand@qpage.ir "sepand@qpage.ir"). 



## Contribution			

You can fork the repository, improve or fix some part of it and then send the pull requests back if you want to see them here. I really appreciate that. ❤️			

Remember to write a few tests for your code before sending pull requests. 



## License

<a href="https://github.com/sepandhaghighi/pycm/blob/master/LICENSE"><img src="https://img.shields.io/github/license/mashape/apistatus.svg"/></a>


## Donate to our project
								
<h3>Bitcoin :</h3>					

```12Xm1qL4MXYWiY9sRMoa3VpfTfw6su3vNq```			



<h3>Payping (For Iranian citizens) :</h3>

<a href="http://www.payping.net/sepandhaghighi" target="__blank"><img src="http://www.qpage.ir/images/payping.png" height=100px width=100px></a>