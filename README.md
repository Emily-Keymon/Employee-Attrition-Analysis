![website](https://user-images.githubusercontent.com/64673015/102019389-f0a8f680-3d38-11eb-8805-57a5716241d2.PNG)

### Website:   https://emily-keymon.github.io/Employee-Attrition-Analysis/
---
# Employee Attrition Analysis
Our project is based around a fictional dataset that gave us various details on employees and whether they attrited or not. The challenge was to incorporate machine learning to give as an algorithm, for a company or manager to use, that determines if an employee will leave their position. This data does not allow the creation of a model that can predict when an employee will leave but rather show you the likelihood of resignation in that current moment based on specific variables. From the dataset, we were given ratings for each employee on the below factors:

* Education
* Environment Satisfaction
* Job Involvement
* Job Satisfaction
* Performance Rating
* Relationship Satisfaction
* Work Life Balance

Education was ranked 1-5, 1 being "Below College" and 5 being "Doctor." Environment Satisfaction was ranked 1-4; "Low" to "Very High." Job Involvement, Job Satisfaction, Performance Rating, Relationship Satisfaction, Work Life Balance all had similar 1-4 rankings, with 1 being "Low" and 4 being "Very High/Outstanding."

Other more straight-forward data points we were given were Age, Gender, Marital Status, Job Title, Travel Time and Years Spent in Position. Most importantly, we were also given each employees Monthly Income and a Yes/No of whether they attrited or not.

---
## Dataset
* https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset

---
## Tools Used
* Jupyter Notebook
* PyCharm - Python IDE
* Python - Pandas, Seaborn, Matplotlib, Numpy, Sklearn
* HTML, CSS, Bootstrap
* Tableau
* Machine Learning models - Linear Regression, Lasso, Ridge, ElasticNet, Decision Tree Classifier, Random Forest, Gradient Boosting

---
## Tasks
### Data exploration 
1.  Imported csv data as a Pandas data frame
2.  Explored data set using Pandas .shape() and .describe()
3.  Visualized the data set using Seaborn and Matplotlib
### Data cleanup
1.  Used get_dummies to convert categorical data into dummy variables to be used for machine learning
2.  Removed extra columns
3.  Renamed columns to remove spacing
### Machine Learning
1.  Assigned cleaned colums as X and y
2.  Trained the model using a seed using train_test_split from sklearn.model_selection
3.  Scaled and fit the model using StandardScaler from sklearn.preprocessing
4.  Tested the data in the following models:  Linear Regression, Lasso, Ridge, ElasticNet, Decision Tree Classifier, Random Forest, Gradient Boosting
### Create visualizations
1.  Data set was imported into Tableau
2. Multiple variables were analyzed including travel frequency, job role, education field, overtime, marital status, age, education level, environment satisfaction and performance rating
3.  Twenty two visualizations were created to represent all the varaibles of the data set
### Website creation
1.  Multi purpose Bootstrap template was used to create framework for website
2.  Modified template with HTML and CSS to align with the data story

---
## Visualizations
### Tableau:  https://public.tableau.com/profile/antonuos.samor#!/vizhome/EMPLOYEE_ATTRITION_PREDICTOR/Story1

---
## Conclusions:
In our review of the data and in our visualizations within Tableau, you can see that there is no single variable which determines attrition rates. There are a few tendencies which become apparent in the data. For example, more single people are at risk of attrition than married people and the average monthly income of those who leave the company is lower than the overall company average. These examples are specific to our dataset, and therefore we needed a model which could be sensitive to them.

Machine learning techniques also confirmed this by showing a very broad importance value range for many different variables. We used the Gradient Booster model for this dataset due to its unique approach to correcting for overfit in complex questions such as this one. Our Gradient Boosting Model enables us to use the outliers to predict using all of the measured variables and correcting as the algorithm runs. While there is no one factor which determines attrition, we can use this model to identify those factors which may make attrition more likely. This means, that now that we have trained this model, we can use similar data to determine the likelihood of attrition for any particular individual. Additionally, we could create a similar model for attrition data in another industry which may have different influential factors.

![by_gender](https://user-images.githubusercontent.com/64673015/102020519-526c5f00-3d3f-11eb-95cb-7a9afc7f794b.PNG)


![by_marital_status](https://user-images.githubusercontent.com/64673015/102020476-1afdb280-3d3f-11eb-9744-82d9d3654080.PNG)


![by_income](https://user-images.githubusercontent.com/64673015/102020485-2355ed80-3d3f-11eb-9177-608d89a06796.PNG)




---
## Sources:
### Boostrap:
* Template Name: Multi
* Template URL: https://bootstrapmade.com/multi-responsive-bootstrap-template/
* Author: BootstrapMade.com
* License: https://bootstrapmade.com/license/
### Images:
* Image 1:  https://www.patriotsoftware.com/wp-content/uploads/2019/03/part-time-vs-full-time-employment-RS13776-compressor.jpg
* Image 2:  https://images.idgesg.net/images/article/2019/08/thumbs-up_happy-employees_binary_diversity_motivated-staff_happy-people_by-peopleimages-getty-100809698-large.jpg
* Image 3:  https://www.bonneystaffing.com/wp-content/uploads/2017/02/AdobeStock_1381193302.jpg
### Other:
* https://corporatefinanceinstitute.com/resources/careers/jobs/attrition-2/

