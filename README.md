# deep-learning-challenge

# Overview
This analysis aimed to create a model that predicts which funding applications to Alphabet Soup are likely to succeed. By analyzing data from over 34,000 organizations, the model helps the foundation make smarter funding decisions.

# Results
Data Preprocessing
Target Variable: IS_SUCCESSFUL, indicating if the funding was used effectively.
Feature Variables: Include application type, affiliation, classification, and others, providing a broad view of each application.
Variables Removed: Identification columns like EIN and NAME, which aren't useful for prediction.
Model Configuration
Model Setup: The model used two hidden layers with 8 and 5 neurons, respectively, and ReLU and sigmoid activation functions. This setup was chosen to balance complexity and performance.
Performance: The initial model didn't hit the desired performance, leading to several adjustments.
Improvements: Adjustments included changing neuron counts, tweaking activation functions, and refining data preprocessing to enhance model accuracy.

# Summary and Recommendations
The deep learning model shows promise but requires adjustments for optimal performance. An alternative approach, such as using a Random Forest Classifier, might offer a simpler, more effective solution. Random Forest can handle categorical data well and might provide better insight into what makes an application likely to succeed. Testing this model against the deep learning approach could give Alphabet Soup the best tool for making funding decisions.
