# To-be-or-Not-to-be

This is a machine learning project in which I predicted whether a person will die or not based on the attributes given in the training dataset and I was 76% successful in predicting the correct answer on the test dataset which is well evident from the screenshot (Result Sheet Codalab.jpg) of the result given in this repository itself.

This project explored the impact of machine learning to predict disease and associated mortality. 
It is used to predict whether a person will die or not based on his medical record, which had 324 features, e.g. age, heart rate, infection, ethnicity, headache. It can be used by doctors to prioritize between patients. The dataset had data of about 80,000 patients. It had many missing values, and it was an imbalance dataset. Only about 20% of patients were to die. My major contribution was in the data preprocessing, filling the missing data with mode, mean, or median. I also did manual dropping of columns, (language, religion, hospital id). I removed the single-value features. We used one-hot encoding to convert categorical variables to numeric. To handle the imbalance, I used Synthetic Minority Oversampling Technique. To extract the most important features, I used a correlation matrix.
I developed algorithmic models, which when combined with neural networks, can enhance predictive ability of the illness and enable the providers to focus more time with patients. This learning gave me a perspective of how AI possesses the potential of more accurate medical practices.

I compared different classification algorithms and after the entire analysis made a final jupyter notebook named as Final.ipynb in this repository to give the entire overview of the project.

The link to competition as well as the link to the datasets is given as follows:
https://competitions.codalab.org/competitions/22873


