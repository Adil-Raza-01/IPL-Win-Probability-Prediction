\# IPL Win Probability Prediction



\## Project Overview



\*\*IPL Win Probability Prediction\*\* is a Machine Learning project that estimates the probability of a chasing team winning an IPL match after the completion of 10 overs.



The project uses historical IPL match data and match situations to predict the chasing team's winning probability.



\## Project Objective



The main objective is to understand how the match situation after 10 overs affects the chances of winning a cricket match.



The model considers three important features:



\- \*\*Runs Required:\*\* Total runs remaining to achieve the target.

\- \*\*Wickets in Hand:\*\* Number of wickets remaining.

\- \*\*Runs in Last 3 Overs:\*\* Runs scored during overs 8, 9, and 10.



\## Dataset



\- \*\*Source:\*\* \[Cricsheet](https://cricsheet.org/downloads/)

\- \*\*Total eligible matches:\*\* 1,171

\- \*\*Data format:\*\* JSON

\- \*\*Skipped matches:\*\* 72



The dataset was processed to extract match situations after 10 overs.



\## Technologies Used



\- Python

\- Pandas – Data manipulation and analysis

\- NumPy – Numerical operations

\- JSON – Match data extraction

\- Scikit-learn – Machine Learning models and evaluation

\- Matplotlib – Data visualization

\- Google Colab – Development environment



\## Machine Learning Models



Three models were implemented and evaluated:



1\. Logistic Regression (1 Feature)

2\. Logistic Regression (3 Features)

3\. Decision Tree Classifier (3 Features)



\## Model Performance



The models were evaluated using ROC-AUC.



| Model | ROC-AUC |

|---|---:|

| Logistic Regression (1 Feature) | 0.915 |

| Logistic Regression (3 Features) | \*\*0.921\*\* |

| Decision Tree (3 Features) | 0.886 |



\*\*Best Model:\*\* Logistic Regression with 3 Features.



\## Example Prediction



For a match situation with:



\- Target Score: 170

\- Current Score: 85

\- Wickets Lost: 1

\- Runs in Last 3 Overs: 30



The model predicts a winning probability of approximately \*\*77.89%\*\* for the chasing team.



\## Project Structure



```text

IPL-Win-Probability-Prediction/

│

├── IPL\_Win\_Probability\_Prediction.ipynb

├── machine\_learning\_report.docx

├── ppt machine learning.pptx

└── README.md

```



\## How to Run



1\. Download or clone this repository.

2\. Open the Jupyter Notebook in Google Colab.

3\. Download the IPL JSON dataset from \[Cricsheet](https://cricsheet.org/downloads/).

4\. Upload and extract the dataset in Google Colab.

5\. Run all notebook cells.

6\. Enter match details in the interactive prediction section to obtain the winning probability.



\## Project Limitations



\- Predictions depend on the selected match features.

\- The dataset contains historical match information.

\- Actual match outcomes can be influenced by several factors not included in the model.

\- Predictions represent estimated probabilities, not guaranteed outcomes.



\## Future Scope



\- Develop a web application using Streamlit.

\- Add more match-related features.

\- Improve model performance through additional algorithms.

\- Provide an interactive interface for real-time match situation analysis.



\## Author



\*\*Adil Raza\*\*



B.Tech – Computer Science and Engineering (Artificial Intelligence and Machine Learning)



\---



\*Developed as a group academic project for Introduction to Machine Learning.\*

