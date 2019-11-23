    Machine Learning Final Project
------

Signup: [Google Sheet](https://docs.google.com/spreadsheets/d/1BU4AssSIvDE4IYBcCWG9bEbyRu0Ql90MqO962MudS-E/edit#gid=0)   
### Learning Outcomes:

- Formulate a meaningful and answerable Data Science research question.
- Munge real data.
- Create and tune a machine learning model.
- Communicate your process and findings to a technical audience.
- Write working and well-organized code.

You should follow the Data Science Workflow:

1. Ask the right question.
2. Acquire the relevant data.
3. Process the data.
4. Model the data with machine learning.
5. Deliver: Create presentation and Jupyter Notebook.

These steps are iterative (do a little preprocessing, do a little modeling, redo the preprocessing, …).

This project will become a part of your public Data Science portfolio, thus all data must be public data.  

Make your own groups of 3 students (a single group with 4 students is okay) within each section.

----

1. Ask.

	This is your project so it is up to your team to develop the right question. 

2. Acquire.
	
	It is best if your team picks a single, unique dataset. The instructor will approve the data to make sure it is appropriate and within scope.

    The dataset should be primarily tabular. No image data is allowed. A small amount of text data is okay, but it should a minor set of features.

	Acquiring data should not take away from the other aspects of the project (i.e., no collecting or web scraping the data). 

3. Process.

	What specific munging issues do you have to address (e.g., encoding, missing data, or data to exclude)? What descriptive/summary statistics are useful for understanding your data? What figures provide insight into your data?

3. Model.

	You must fit at least 2 different types of algorithms and compare results. For example, your team could pick logistic regression and Random Forest™. Or your team could pick k-means clustering and spectral clustering.

    Each algorithm's hyperparameters should be tuned.

5. Deliver(ables).

    There are two deliverables:

    1. An in-class presentation either on 12-03-19 (section 1) or 12-06-19 (section 2). The presentation will be 6 minutes with 1 minute of questions and (hopefully) answers.
    2. A GitHub repository is due on 12-11-19 by 6pm.

    The GitHub repo should be public with a single Jupyter Notebook notebook. 

    I except that single Jupyter Notebook to be reproducible (i.e., it will run on other people's computers). Thus, I suggest creating a conda enviroment for your project to manage dependencies.

    Regarding data managment, that Jupyter Notebook should read in a single dataframe. If that single dataframe is small, it can committed to the GitHub repo. If that single dataframe is too large for GitHub, store the data on a public file sharing service (e.g., AWS S3) and code within the Jupyter Notebook should fetch it.

    All other work should somewhere else and will not be graded. 

----
Hints
----

- Make it run, make it right, make it fast. (in that order)
- Go end-to-end as quickly possible. From raw data -> basic features -> simple model -> evaluation. Then explore options for each stage.
- How do I get a "A"? 
    - Do something groundbreaking (seriously). Either ground-breaking for the field or for the class.
    - Fit models and use methodologies from outside class materials.
    - Error bars!!!

----
FAQs
-----

1. Can I use \_\_\_\_\_\_\_\_ software package?

    The goal of this project to review the course materials, this course has been in Python and using scikit-learn package. You should only use Python. The majority of your code should be in scikit-learn.

    There should be __no__ Spark, TensorFlow, or PyTorch code anywhere. 

    Do __not__ reimplement any algorithm or function. If possible, call existing code. If possible, call scikit-learn code. Only use Pandas, NumPy, or SciPy if scikit-learn does not have the functionality you require.

    Visualizations are important for understanding your system and communicating to your audience. Visualizations should be clear; They do not need to be beautiful. You can use any Python visualization package, suggestions are Matplotlib and Seaborn.

    You can use any third party Python packages. Try to use packages that are related to scikit-learn, see list [here](https://scikit-learn.org/stable/related_projects.html).


1. For the Final Project, how will model performance on my chosen evaluation metric effect my grade?

    Absolute model performance on evaluation metrics will have __no__ impact the grade. There are many different datasets, each one will perform differently. This is different from the assignments where absolute model performance on evaluation metrics was important because everyone use the same datasets.

    What will impact your team grade is relative model performance on the evaluation metrics. I except your team try different combinations of features, algorithms, and hyperparameters. You should find a combination that does better as measured by evaluation metrics.

    Selecting the evaluation metric will impact your team grade. You should select metric(s) that are relevant for the research question, not something that you can easily maximize.




