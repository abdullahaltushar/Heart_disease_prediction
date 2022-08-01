<h1 align="center">
	<img src="https://readme-typing-svg.herokuapp.com?size=35&color=8B65F7&width=600&height=70&lines=Heart+Disease+Prediction!%F0%9F%92%9F"> 
</h1>

## 👀 Introduction
Thus preventing Heart diseases has become more than necessary. Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives. This is where Machine Learning comes into play. Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.

## 👩‍💻 Technology Stack
#### ✒️**Language**
![Python](https://img.shields.io/badge/python-000066?style=for-the-badge&logo=python&logoColor=silver)
#### 🧰**Tools**
 ![Numpy](https://img.shields.io/badge/Numpy-000000?style=for-the-badge&logo=numpy&logoColor=silver) ![Pandas](https://img.shields.io/badge/Pandas-3c0152?style=for-the-badge&logo=pandas&logoColor=silver) ![Matplotlib](https://img.shields.io/badge/Matplotlib-40001c?style=for-the-badge&logo=matplotlib&logoColor=silver)![Scikit Learn](https://img.shields.io/badge/-Scikit%20Learn-%23f50000?style=for-the-badge&logo=transformer&logoColor=silver)


## 🔭: Problem Definition
<p>In our case, the problem we will be exploring is binary classification (a sample can only be one of two things).
This is because we're going to be using a number of differnet features (pieces of information) about a person to predict whether they have heart disease or not.</p>

## 📘: Data
<p>Ther is also a version of it avalable on Kaggle.
The original database contains 76 attributes, but here only 12 attributes will be used. Attributes (also called features) are the variables what we'll use to predict our target variable.
Attributes and features are also referred to as independent variables and a target variable can be referred to as a dependent variable.</p>

## 🛗: Evaluation
<p> he evaluation metric is something you might define at the start of a project.
Since machine learning is very experimental, you might say something like,
If we can reach 93% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursure this project.
The reason this is helpful is it provides a rough goal for a machine learning engineer or data scientist to work towards.
However, due to the nature of experimentation, the evaluation metric may change over time.</p>

## 🛶: Features
<p>Features are different parts of the data. During this step, you'll want to start finding out what you can about the data.
One of the most common ways to do this, is to create a data dictionary.
Heart Disease Data Dictionary
A data dictionary describes the data you're dealing with. Not all datasets come with them so this is where you may have to do your research or ask a subject matter expert (someone who knows about the data) for more.
The following are the features we'll use to predict our target variable (heart disease or no heart disease).

- age - age in years
	- sex - 1 = male; 0 = female
- chest pain type
	- 0: Typical angina: chest pain related decrease blood supply to the heart
	- 1: Atypical angina: chest pain not related to heart
	- 2: Non-anginal pain: typically esophgael spasms (non heart related)
	- 3: Asymptomatic: chest pain not showing signs of disease
- Resting bp s- resting blood pressure (in mm Hg on admission to the hospital)
- cholesterol - serum cholestoral in mg/dl
	- serum = LDL + HDL + .2 * triglycerides
	- above 200 is cause for concern
- fasting blood sugar- (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
	- '>126' mg/dL signals diabetes
- Resting ecg - resting electrocardiographic results
	- 0: Nothing to note
	- 1: ST-T Wave abnormality
		- can range from mild symptoms to severe problems
		- signals non-normal heart beat
	- 2: Possible or definite left venticular hypertrophy
		- Enlarged heart's main pumping chamber
- Max heart rate- maximum heart rate achieved
- Exercise angina- exercise induced angina (1 = yes; 0 = no)
- oldpeak - ST depression induced by exercise relative to rest
	- looks at stress of heart during excercise
	- unhealthy heart will stress more
- ST slope - the slope of the peak exercise ST segment
	- 0: Unsloping: better heart rate with excercise (uncommon)
	- 1: Flatsloping: minimal change (typical healthy heart)
	- 2: Downsloping: Signs of unhealthy heart
- target - have disease or not (1=yes, 0=no)(= the predicted attribute)
</p>

## ✅: Modeling
<p>We've explored the data, now we'll try to use machine learning to predict our target variable based on the 11 independent variables.
Remember our problem?
Given clinical parameters about a patient, can we predict whether or not they have heart disease?
That's what we'll be trying to answer.
And remember our evaluation metric?
If we can reach 92% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursure this project.
That's what we'll be aiming for.
But before we build a model, we have to get our dataset ready.
</p>
## 👁️‍🗨️: Model choices
<p>
- Now we've got our data prepared, we can start to fit models. we'll be using the following and comparing their results.
	- Logistic Regression
	- K-Nearest Neighbors 
	- RandomForest 
	- Decision Tree
	- Neural Network
</p>


    Logistic Regression (Scikit-learn)
    Decision Tree (Scikit-learn)
    Random Forest (Scikit-learn)
    Artificial Neural Network with 2 Hidden layer (Keras)
