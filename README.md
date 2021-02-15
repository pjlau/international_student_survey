
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from IPython import display
import seaborn as sns
from sklearn.model_selection import train_test_split
import statsmodels.api as sm

All libraries cited in the code are pre-installed along with the Anaconda distribution of Python. The code should be executable using Python versions 3.*.


## Project Motivation<a name="motivation"></a>

This project took a deeper look at a survey on a small international student body conducted in 2019. I would like to know which demographic tend to do well/poorly and what can be improved in the course design to help them do better or be more interested. Thus, I would like to answer a few questions by analyzing the survey data:

1. Which age group demonstrates the best academic performance?
2. Which program has the students tend to perform well?
3. Which survey question has the highest correlation to grade performance of the students?
4. Does attending the classes help the students getting better grade?


The full set of files related to this course are owned by Udacity, so they are not publicly available here.  However, you can see pieces of the analysis here.  This README also serves as a template for students to follow in creating their own project README files.


## File Descriptions <a name="files"></a>

There are 3 notebooks available here to showcase work related to the above questions.  Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  Markdown cells were used to assist in walking through the thought process for individual steps.  

There is an additional `.py` file that runs the necessary code to obtain the final model used to predict salary.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://jimpikkin.medium.com/a-quick-glance-of-student-time-management-vs-performance-8b1815e2d5).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Otherwise, feel free to use the code here as you would like! 

