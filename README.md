<span style="color:red"><center><h1>DRAFT</h1></center></span>

<center><h2>University of San Francisco's Machine Learning Laboratory <br>  MSDS 699 Fall 2019</h2></center>

<center><img src="https://imgs.xkcd.com/comics/machine_learning.png" style="width: 40%"/></center>

> "It's tough to make predictions, especially about the future."   
> – Yogi Berra   

----
Course Description
----

In this course, you'll create end-to-end solutions to machine learning problems with increasing complexity. This course will cover common applied techniques in both supervised and unsupervised machine learning, such as regression, classification, and clustering. 

Algorithms will include Generalized Linear Models (GLM), k-Nearest Neighbors (k-NN), Naive Bayes, Decision Trees, Random Forests, and k-Means Clustering. Machine learning is about much more than the algorithms themselves. The methodology surrounding the algorithms is just as important as the algorithms. You'll learn to properly engineer features, evaluate model performance, and communicate the results to both technical and non-technical audiences.

This course is a lab course associated with the MSDS Intro to Machine Learning (MSDS 621). MSDS 621 focuses on the implementation of machine learning algorithms. Whereas in this lab, you'll learn to use pre-existing implementations of these machine learning algorithms from Python's [scikit-learn](https://scikit-learn.org) library.  

----
Logistics
----

__Instructor:__ Brian Spiering   
__Contact__: [Slack DM](https://msan-usf.slack.com/messages/DAMAXHTL5) (more preferred) | [bspiering@usfca.edu](mailto:bspiering@usfca.edu) (less preferred)  
__Office hours__: Tuesdays & Thursdays 2:15-3:10 in 522 & By Appointment   

__Grader__: TBD     
__Contact__: [Slack DM](https://msan-usf.slack.com/messages/TBD) | [TBD@usfca.edu](TBD@usfca.edu)  
__Office hours__: By appointment  

__Website__: [github.com/brianspiering/tbd](https://github.com/brianspiering/tbd)    
__Communication__: Slack [`#ml_lab_2019`](https://msan-usf.slack.com/messages/CNCN8CU9Y)  

Prerequisites
----

- Working knowledge of probability and statistics
- Introductory knowledge of linear algebra (e.g., determinants and Singular Value Decomposition)
- Intermediate level of Python (e.g., ability to create to classes)
- No previous knowledge of machine learning required

Learning Outcomes
-----

By the end of the course, you should be able to:     
1. Apply fundamental machine learning models and methodology to solve real-world problems. 
1. Write idiomatic Python code to model data. Primarily using the scikit-learn package. 
1. Define common machine learning terms and identify applied examples.
1. Explain common regression, classification and clustering algorithms.
1. Recognize when to and _when not to_ apply machine learning algorithms.
1. Build end-to-end machine learning models to an answer meaningful Data Science questions.

-----
Course Schedule and Topics (Tentative)
-----

Sections:

1. Tuesdays  at 3:15pm-5:05pm in Room 529 
2. Thursdays at 3:15pm-5:05pm in Room 529    

You have been assigned a specific section for this course. You __must__ attend the section you have been assigned!

Format: Number. Date (Section) | Date (Section)

1. 10/17 (2) | 10/22 (1)
    - Machine learning modeling process
    - Train-test split
    - Modeling fitting in scikit-learn 
    - Regression models
    - Regression metrics    
    - Continuous features

2. 10/24 (2) | 10/29 (1)
    - Cross-validation split
    - Classification models
    - Classification metrics
    - Categorical features and 1-hot encoding 

3. 10/31 (2) | 11/05 (1)
    - Linear models
    - Cross-validation techniques (Leave-one-out testing & k-fold)
    - Hyperparameters tuning with grid search and random search
    
4. 11/07 (2) | 11/12 (1)
    - Tree-based models
    - Out-of-bag (OOB) error
    - Feature engineering with normalization and standardization 
    - Pipeline in scikit-learn
    
5. 11/14 (2) | 11/19 (1)
    - Feature engineering:
        - Date-based data
        - Strings
        - Dimension reduction
    - Non-stationary data
   
6. 11/21 (2) | 11/26 (1)
    - Unsupervised machine learning
    - Clustering 

7. 12/03 (1) | 12/06 (2)
    - Final Presentations

Topics Not Covered
-----
- Theory (no proofs 🙂)
- Research (this is an applied course 🔨)
- Implementing algorithms (covered in MSDS 621 🤔)
- R programming language  (Python only 🐍)
- Data acquisition (assume tabular data 📋)
- Visualization (just basic plotting with matplotlib and Seaborn 📊)
- Optimization (assume that we have decent solver 📉)
- Productizing models (let the Data Engineers do that 👷)
- Distributing models (let AMZN and GOOGL do that for you 📈)
- Bayesian approach (I wish we could… 😫)
- Anomaly Detection (not enough time to get strange 👽)
- Recommender Systems (covered later in MSDS 630 ⌛)
- Reinforcement Learning (we don't have time to play games 👾)
- Ethics (not enough time to think about implications 🤔)
- Algorithms
    - Boosting
    - Neural Networks / Deep Learning
    - Graphical Models / Bayes Nets
    - Linear Discriminant Analysis (LDA)
    - Expectation–Maximization (EM)  
    - Gaussian Mixture Models (GMM)
    - Advanced clustering:
        - DBSCAN 
        - Hierarchical 
        - Mean-Shift 

----
Textbooks
----

There are no required textbooks. 

The following excellent books are optional for reference:

- [Machine Learning with Python Cookbook: Practical Solutions from Preprocessing to Deep Learning](https://www.amazon.com/Machine-Learning-Python-Cookbook-Preprocessing/dp/1491989386) by Chris Albon
- [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646) 2nd Edition by Aurélien Géron 
- [Feature Engineering for Machine Learning: Principles and Techniques for Data Scientists](https://www.amazon.com/dp/B07BNX4MWC) by Alice Zheng and Amanda Casari

----
Grading
----

| Item               | Weight | Due Date & Time |
|:-------------------|:------:|:------------:|
| Professionalism    | 10%    | Throughout   |
| Assignment 1       | 10%    | 10/27 at 9p  |
| Assignment 2       | 10%    | 11/03 at 9p  |
| Assignment 3       | 10%    | 11/10 at 9p  |
| Assignment 4       | 10%    | 11/17 at 9p  |
| Assignment 5       | 10%    | 11/24 at 9p  |
| Final Project (FP) | 40%    | 12/11 at 6p <sup>†</sup>  |
| __Total__          | __100%__ | |

† In-class presentations will be on 12/03 or 12/06. The written report will be due on 12/11.

Each item's contribution is capped its respective percentage. The total course percentage is capped at 100%.

Currently, there is no extra credit. If there is any extra credit, it is entirely at the discretion of the instructor.

We'll be using Canvas as the learning management system (LMS), aka the gradebook. The instructional team will do their best to have Canvas accurately reflect your current scores in the course. However, Canvas may not be completely accurate all the time. In other words, your actual grade maybe significant different than it appears on Canvas. 

Late assignments will only be accepted for medical emergencies.

Asking for acceptance of any late assignments without a medical emergency or submitting assignment not through Canvas will result in a loss of professionalism points (and your assignment will still not be accepted).

### Professionalism

I expect you act professionally in-person (both inside and outside the classroom) and electronically. Since people come up from a variety of backgrounds, I want to be explicit about the elements of professionalism: 

- Show up on time and prepared.
- Remain fully present.
- Contribute appropriately and meaningfully.
- Follow staff and faculty instructions appropriately.
- Show respect to all people.

Professionalism points are entirely at the instructor's discretion. 

Violations of Academic Integrity are unprofessional, thus you'll automatically lose all Professionalism points for any violations of Academic Integrity.

I try to create an active learning environment in my classroom. Attendance is mandatory - you can't participate if you don't attend. It is the responsibility of the student to attend all classes. If you have to miss class, due to sickness, job interviewing, or other circumstances, please notify your instructor by Slack in advance. Supporting documents (e.g., doctor’s notes) may be asked for.

Tardiness negatively impacts an active learning environment, thus will impact your professionalism grade.

You must show-up to each session prepared. 

Each person is important to the dynamic of the class, and therefore students are required to participate in class activities. Expect to be "cold called". I call on students at random not to put you on the spot but to keep you engaged in the material at all times.

This is a closed-computer classroom. Your phone and laptop must stay put away during the entire class, unless explicitly instructed by me that it is okay to use your laptop for a specific activity. I have observed that just the presence of phones and laptops negatively impacts the learning experience for everyone in the classroom. I expect you to be fully present and engaged in the classroom at all times. I _strongly_ suggest taking notes on paper. A tablet is acceptable for note-taking. A tablet should __not__ be used for any other purpose.

This is your warning for off-topic computer use. Violations include (but not limited to): looking at the screen, typing, and using any type of computer for activities not directly to the current in-class activities. Every violation will negatively impact your total grade by losing professional points. The penalties scale exponentially - The first offense is will result in a 1% loss of total points, the second offense is 5% of total points, the third offense is 10%, the fourth offense is 15%, and the fifth offense is 20% of total points (i.e., the cap is 100% of your professional points). 

### Assignment

The assignments will be hands-on activities. They will require a combination of coding and writing. The coding sections will be using Python's scikit-learn, numpy, and pandas libraries to model data. The writing sections will focus on communication to technical and nontechnical audiences.

### Final Project 

In lieu of a Final Exam, there will be a Final Project. Details in Final Project Folder.

Grading standards
----

The MSDS program considers a grade of "A" to represent exceptional work with respect to both the instructor's expectations and peer student achievements. I consider an "A" grade to be above and beyond what most students achieve. A grade of "B" represents the expected outcome, what is called "competence" in a business setting. A "C" grade represents achievements lower than the instructor's expectations for competence in the subject. A grade of "F" represents little or no work in the course.

I will "curve" the final numerical grades at the end of the course. The mapping from percentages to letter grades (e.g., [95, 100] is an A, [90,95) is an A-, etc.) will not be established until the end of the course. Roughly, the top 15% of students will receive grades of A or A-. Roughly, 60% of students will receive grades of B+, B, or B-. Roughly, 20% of students will receive grades of C+, C, or C-. Students can receive failing grades. 

Students with disabilities
-----

If you are a student with a disability or disabling condition, or if you think you may have a disability, please contact [USF Student Disability Services](https://myusf.usfca.edu/sds) (SDS) for information about accommodations.

Behavioral Expectations
----

All students are expected to behave in accordance with the [Student Conduct Code](https://myusf.usfca.edu/fogcutter) and other University policies.

Academic Integrity
-----

USF upholds the standards of honesty and integrity from all members of the academic community. All students are expected to know and adhere to the University's [Honor Code](https://myusf.usfca.edu/academic-integrity/).

If you ever have questions about what constitutes plagiarism, cheating, or academic dishonesty in my course, please feel free to ask me.

Counseling and Psychological Services (CAPS)
-----

CAPS provides confidential, free [counseling](https://myusf.usfca.edu/student-health-safety/caps) to student members of our community.

Confidentiality, Mandatory Reporting, and Sexual Assault
-------

For information and resources regarding sexual misconduct or assault visit the [Title IX](https://myusf.usfca.edu/TITLE-IX) coordinator or USF's [Callisto website](http://usfca.callistocampus.org/).
