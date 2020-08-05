# Equation Evaluator
The aim of this project is to digitize the evaluation of handwritten equation.
# Work Flow
The work flow is as follows
![img_work_flow](https://github.com/gd1m3y/Equation-Evaluater/blob/master/work_flow.png?raw=true)

* Workspace Detection module -  is responsible for detecting multiple workspaces in a given sheet of paper using pre-defined markers.
* Analysis Module - is responsible for detecting and localizing characters in lines in any given single workspace, and mathematically analyzing them and then drawing red, green lines depending upon their correctness.
# Model Architecture 
DCNNN
![img_work_flow](https://github.com/gd1m3y/Equation-Evaluater/blob/master/deepcnn.png?raw=true)

#  Features

  - Light weight
  - Very easy to use and customize
  - highly accuracte

### Tech

Equation Evaluater uses a number of open source projects to work properly:

* [Python] - Python 3.6 the mother of data science languages
* [Pycharm] - awesome python editor
* [Open-Cv] - Open-cv version 4.3.3
* [tensorflow 2.X] - a deep learning framework
### Installation

Chat bot 0  requires python 3.6 with following libraries:
* tensorflow-2.x 
* Open cv
* numpy
* immutils

if you are using conda env you can create a conda enviorment with python 3.6
```sh
conda create env python ==3.6
pip install tensorflow==1.4

```
# Example
the following image shows the result

![img_work_flow](https://github.com/gd1m3y/Equation-Evaluater/blob/master/result.png?raw=true)

### Development

Want to contribute? Great!

contact me at narayanamay123@gmail.com
### Todos

 
 - Re-train the model in a better data set
License
----

MIT
