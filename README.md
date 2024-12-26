## Jamboree Business Case
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

### Role of Data Scientist
1. Analyzing the features of the dataset by performing exploratory data analysis. Thereby, determining the importance of each feature in predicting the target variable which is _Chance of Admit_ column in the given dataset. 
2. Training the dataset using appropriate machine learning algorithm.
3. Evaluating the model with respect to suitable metrics
4. Hypertuning the obtained model to get better predictions. 

### Steps followed while building the model for Jamboree Case study:
1. Exploratory data analysis
    a. Understanding the structure of data
  b. Checking for Null values.
  c. Univariate analysis for categorical columns
  d. Univariate analysis for numerical columns
  e. Bivariate analysis 

2. Data preprocessing 
  a. Separating features and Target variable.
  b. Data Normalization
  c. Spliting the data into train and test datasets

3. Implementation of Linear regression model
  a. Linear Regression from scratch
  b. Using scikitlearn library
  c. Using OLS

4. Assumptions of Linear Regression
5. Implementation of Polynomial regression to achieve better R2
6. Implementation of Lasso, Ridge and Elastic Net Regressions to balance both Under-fitting and Overfitting cases.

Overall achieved a R2 score of 0.82.
### Column profiling
| Feature | Description |
|:--------|:------------|
|Serial No.| This column represents the unique row identifier for each applicant in the dataset.|
|GRE Scores| This column contains the GRE (Graduate Record Examination) scores of the applicants, which are measured on a scale of 0 to 340.|
|TOEFL Scores| This column includes the TOEFL (Test of English as a Foreign Language) scores of the applicants, which are measured on a scale of 0 to 120.|
|University Rating| This column indicates the rating or reputation of the university that the applicants are associated with , & The rating is based on a scale of 0 to 5, with 5 representing the highest rating.|
|SOP|This column represents the strength of the applicant's statement of purpose, rated on a scale of 0 to 5, with 5 indicating a strong and compelling SOP.|
|LOR| This column represents the strength of the applicant's letter of recommendation, rated on a scale of 0 to 5, with 5 indicating a strong and compelling LOR.|
|CGPA| This column contains the undergraduate Grade Point Average (GPA) of the applicants, which is measured on a scale of 0 to 10.|
|Research| This column indicates whether the applicant has research experience (1) or not (0).|
|Chance of Admit| This column represents the estimated probability or chance of admission for each applicant, ranging from 0 to 1.|

