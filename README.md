# Estimation, machine learning and testing

## Contents:
1. [Description](https://github.com/UofT-DSI/estimation_machine_learning_testing#description)
2. [Learning Outcomes](https://github.com/UofT-DSI/estimation_machine_learning_testing#learning-outcomes)
3. [Logistics](https://github.com/UofT-DSI/estimation_machine_learning_testing#logistics)
4. [Class Schedule](https://github.com/UofT-DSI/estimation_machine_learning_testing#class-schedule)
5. [Grading Scheme](https://github.com/UofT-DSI/estimation_machine_learning_testing#grading-scheme)
6. [Acknowledgements](https://github.com/UofT-DSI/estimation_machine_learning_testing#acknowledgements)

## Description
This course provides the intuition and skills required to design, implement, test and validate a variety of supervised learning models. We cover the basics of statistical learning including modelling with the goal of prediction versus inference, prediction accuracy and model interpretability trade-off, and the bias-variance trade-off. Each section of this course will cover a unique set of methods used for supervised learning on real data sets.

## Learning Outcomes
By the end of the course, students will:
1. Understand, implement and interpret the results from several supervised learning approaches for regression and classification
2. Utilize resampling methods to extract more information from a data set and to choose the best model
3. Perform exploratory data analysis for unsupervised learning
4. Understand what is required for reproducible learning
5. Appreciate the uncertainties associated with model results and the ethical consequences of acting on these results
6. Communicate different trade offs and considerations for the statistical methods in their toolkit to both technical and non-technical audiences

## Logistics

### Course Contacts
* Instructor: Kamilah Ebrahim [kamilah.ebrahim@mail.utoronto.ca](kamilah.ebrahim@mail.utoronto.ca)
* TA: Ananya Jha [ananya.jha@mail.utoronto.ca](ananya.jha@mail.utoronto.ca)

### Textbook
This course is based largely on the second edition (2021) of *An Introduction with Statistical Learning with Applications in R* (ISLR2), written by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani and *An Introduction with Statistical Learning with Applications in Python* (ISLP), written by Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani, and Jonathan Taylor (2023). Students should choose the language they are most familiar with to complete this course. Whether taken in R or Python, the underlying principles of this course remain the same. This course includes all essential materials from the textbooks in our slides and is not required; however, students may find it useful as a reference. The books can be downloaded for free, online, at the [companion website](https://www.statlearning.com/). If preferred, both the [R](https://librarysearch.library.utoronto.ca/discovery/fulldisplay?docid=alma991106106183406196&context=L&vid=01UTORONTO_INST:UTORONTO&lang=en&search_scope=UTL_AND_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,An%20Introduction%20to%20Statistical%20Learning&offset=0) and [Python](https://librarysearch.library.utoronto.ca/discovery/fulldisplay?docid=alma991107279624206196&context=L&vid=01UTORONTO_INST:UTORONTO&lang=en&search_scope=UTL_AND_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,An%20introduction%20to%20statistical%20learning%20:%20with%20applications%20in%20Python) verions of the books can be purchased, or borrowed from the University of Toronto library in print or online. 

### Technology Requirements
Lectures and tutorials are run synchronously over Zoom. We use R and RStudio and Juypiter Notebooks throughout the course. It is preferrable to have them installed; however, the RStudio IDE may be accessed via the 
the [Posit Cloud](https://posit.cloud/) if preferred (free account required). We will occasionally use [Posit Cloud](https://posit.cloud/) for collaborative coding. 

### Classes
We will have four classes a week for two weeks. Classes are 6 PM - 8:30 PM EST on Tuesday, Wednesday and Thursday, and 9 AM - 11:30 AM EST on Saturdays. Being mindful of online fatigue, there will be one or two brief breaks during each class.

Classes will consist of instruction via prepared slides, and live-coding. All slides will be made available before lectures online. Students should perform coding in real-time, alongside the instructor. Students are encouraged to ask questions at any time. As required, we will use Zoom Whiteboard to work through 'pen and paper'-type questions, and Posit cloud to work through coding puzzles.

### Tutorial
Tutorial sessions are on the same date as each class. Tutorials will take place 30 minutes before and after each session. Tutorial attendance is optional, and organization is unstructured. The tutorial is the best place for questions/issues pertaining to software, homework, and assignments.

## Class Schedule

### Class Topics

| Class | Date                   | Topic                                                                               |  Resources | ISLR2/ISLP Chapter |
|--------|------------------------|-------------------------------------------------------------------------------------|------------| --------|
| 1      | Tuesday 16 January    | Key Concepts <br> Simple linear regression       | [Slides 1/2](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.1-Introduction_to_Statistical_Learning_slides.pdf); [Slides 2/2](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.2-Linear_Regression_slides.pdf) | 2,3
| 2      | Wednesday 17 January   | Multiple linear regression, interactions, qualitative predictors <br>                         | [Slides](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.2-Linear_Regression_slides.pdf) | 3            
| 3      | Thursday 18 January   | Classification (logistic regression, generative models)                     | [Slides](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.3-Classication_slides.pdf) | 4                    
| 4      | Saturday 20 January     |  Resampling methods (CV, bootstrap) and Linear model selection and regularization         | [Slides1/2](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.4-Resampling_Methods_slides.pdf)[Slides2/2](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.5-Linear_Model_Selection_and_Regularisation_slides.pdf)  | 5, 6               
| 5      | Tuesday 23 January      | Beyond linearity                                       | [Slides](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.6-Beyond_Linearity_slides.pdf)| 7       
| 6      | Wednesday 24 January       | Tree-based methods                           | [Slides](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.7-Tree-Based_Methods_slides.pdf) | 8        
| 7      | Thursday 25 January       | Professional Skills - Industry Case Study  <br>(Guest: Ajit Desai, Bank of Canada)  | | NA                  
| 8      | Saturday 27 January         | Survival Analysis, Principal Components Analysis, Ethics/Inequity/Reproducibility | [Slides 1/2](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.10-Unsupervised_Learning_slides.pdf), [Slides 2/2](https://github.com/UofT-DSI/06-statistical_learning/blob/main/lessons/6.9-Survival_Analysis_and_Censored_Data_slides.pdf)| 12, 13                       

## Grading Scheme

Grading is based on three components: 3 assignments, 5 homework questions (completion only), and class participation. The grading scheme is as follows:

| Assessment       | Number |  Individual Weight | Cumulative Weight
|------------------|--------|--------------------|------------------|
| Assignments      | 3      |  25%               | 75%              |
| Homework         | 5      |  3%                | 15%              | 
| Participation    | NA     |  NA                | 10%              |

**Assignments**

Assignments will cover key statistical concepts and related code implementation. One assignment is assigned per week, for three weeks, for a total of 3 assignments. Assignments will be introduced in class, can be discussed in tutorial, and questions can be ask of the Instructor and/or TA over email. Assignments are due by midnight on Sundays and Thursday. Please arrange for extensions *in advance* with the Instructor. Assignments should be submitted through the correct Google Forms link found below following the naming convention `firstname_lastname_a#`.

Assignments can be found in the `Assignments` directory, above. We've included an .html file (knitted Markdown file) for easy reading, as well as Jupyter Notebook files, that can be edited for submission. (To download files, click Raw > Save as.)

Note: If the assignment requires some content we end up not covering in class (i.e., we've fallen behind), it will be removed from the assignment / not be graded (you're welcome to submit answers if you like). Any questions that are removed will be determined and clearly indicated in the class before the assignment is due.

**Assignment Due-dates**

| Assessment        | Content         | Due Date                         | Submission Link |
| ------------------| ----------------|----------------------------------| ------------------ |
| Assignment 1      | Classes 1, 2, 3   |  Sunday 21 January, by midnight | [A1](https://forms.gle/5ocshXh5ZtUj8WXY6) |  
| Assignment 2      | Classes 4, 5, 6   |  Thursday 25 January, by midnight     | [A2](https://forms.gle/nNJMjBRzDVaRKMBA9) |
| Assignment 3      | Classes 7, 9     |  Sunday 28 January, by midnight    | [A3](https://forms.gle/qSnbougKaH5cvntb8) |

**Homework**

For each class (with the exception of the Industry Case Study and the first class), one homework question from the ISLR2 textbook will be assigned. The homework question is graded for **completion only** (i.e., an attempted solution receives full marks), and *only 5 questions* are required over the course (i.e., you do not have to submit 3). The homework questions will require writing code in Python and are designed to take no more than 20 minutes. Individual feedback is not provided on the weekly homework question by default, but will be discussed in tutorials. Homework questions must be submitted before the beginning of the next class; late submissions will not be graded. Homeworks should be submitted through the correct Google Forms link found below following the naming convention firstname_lastname_hw#.  

Homework is as follows (<u>only 5 required, marked for competion only!</u>):

| Assessment        | ISLR2 Question       | ISLP Question       |           Due Date | Submission Link |
| ------------------| ---------------------|----------------------|---------------------| --------------- |
| Homework class 1   | Ch 3, pg 123, q8    | Ch 3, pg 129, q8     |Wednesday 17 January, by 6pm | [HW1](https://forms.gle/hyZwATUZaeq8tCMt8) | 
| Homework class 2   | Ch 3, pg 123, q9, a-e | Ch 3, pg 129-130, q9, a-e | Thursday 18 January, by 6pm| [HW2](https://forms.gle/oXC5jCkUeTXP5r5U6) | 
| Homework class 3   | Ch 4, pg 193, q13    | Ch 4, pg 196-197, q13 | Saturday 20 January, by 9am| [HW3](https://forms.gle/oXC5jCkUeTXP5r5U6) |
| Homework class 4   | Ch 5, pg 221, q6     | Ch 5, pg 226-227, q6 | Saturday 20 January, by 9am| [HW4](https://forms.gle/jNg8XrnWbDY6aep28) |
| Homework class 5   | Ch 5, pg 286, q9, a-d| Ch 5, pg 286-287, q9, a-d | Tuesday 23 January, by 6pm| [HW5](https://forms.gle/v8qmqjWBbm83aAUBA) |
| Homework class 6   | Ch 7, pg 324, q9     | Ch 7, pg 327, q9    |  Wednesday 24 January, by 6pm| [HW6](https://forms.gle/ixMWHBrJzW4BgLk16) |
| Homework class 7   | Ch 8, pg 363, q9     | Ch 8, pg 365, q9    | Thursday 25 January, by 6pm| [HW7](https://forms.gle/9tWZjJoYnRV9JYM9A) |
| Homework class 9   | Ch 12, pg 550, q9    | Ch 12, pg 554-555, q9 | Saturday 27 January, by 9am | [HW8](https://forms.gle/NBbS3DmLHJqSy7PL7) |

**Participation**

We hope all members in the course regularly participate. We define participation broadly, and include attendance, asking questions, answering others' questions, participating in discussions, etc.

## Acknowledgements
Rohan Alexander supervised the development of this course. The first slides were developed by Simone Collier. Slides have been created and modified by Navona Calarco and Julia Gallucci for Winter 2023. Materials were re-developed from R to Python by Inessa De Angelis in Fall 2023. This course draws extensively on *An Introduction to Statistical Learning with Applications in R* (2nd edition, 2021), by Gareth James, Daniela Witten, Trevor Hastie, and Robert Tibshirani and *An Introduction to Statistical Learning with Applications in Python* (2023) by Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani, and Jonathan Taylor. 

## To Update
For the course instructor and course support:

  -   Update course assignments and answer keys to reflect new grading approach 
  
      - Specifically, check which assignment Question 4 (assignment 1) / Question 1 (assignment 2) should be included with
  
  -   Update dates, deadlines, and class schedule throughout all materials and this ReadMe
  
  -   Update course instructor and course support names and contract information throughout all materials and this ReadMe
  
  -   Update learning outcomes listed throughout all materials and this ReadMe.
  
  -   Add remaining answers to the Python homework 5 and 7 documents. 
  
  -   This is not so much something to update, but a note! All the Python packages used as part of ISLP are always changing and if you are continually getting error messages when running code, make sure everything is up-to-date by running the following in your terminal: `pip install -r https://raw.githubusercontent.com/intro-stat-learning/ISLP_labs/v2/requirements.txt` . More info: https://islp.readthedocs.io/en/latest/installation.html. 
