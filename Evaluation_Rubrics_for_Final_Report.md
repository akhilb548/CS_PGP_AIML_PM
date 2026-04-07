# Evaluation Rubrics for Final Report

| Section | Description | Points |
|---------|-------------|--------|
| Data Registration | - Create a master folder and create a subfolder "data" <br> - Register the data on the Hugging Face dataset space | 2 |
| Exploratory Data Analysis | - Data collection and background <br> - Data overview <br> - Univariate analysis <br> - Bivariate analysis <br> - Multivariate analysis <br> - Insights/observations based on EDA | 3 |
| Data Preparation | - Load the dataset directly from the Hugging Face data space. <br> - Perform data cleaning and remove any unnecessary columns. <br> - Split the cleaned dataset into training and testing sets, and save them locally. <br> - Upload the resulting train and test datasets back to the Hugging Face data space. | 4 |
| Model Building with Experimentation Tracking | - Load the train and test data from the Hugging Face data space <br> - Define a model and parameters <br> - Tune the model with the defined parameters <br> - Log all the tuned parameters <br> - Evaluate the model performance <br> - Register the best model in the Hugging Face model hub <br><br> *The ML models to be built can be any of the following algorithms, such as Decision Tree, Bagging, Random Forest, AdaBoost, Gradient Boosting, and XGBoost* | 6 |
| Model Deployment | - Define a Dockerfile and list all configurations <br> - Load the saved model from the Hugging Face model hub <br> - Get the inputs and save them into a dataframe <br> - Define a dependencies file for the deployment <br> - Define a hosting script that can push all the deployment files into the Hugging Face space | 12 |
| Automated GitHub Actions Workflow | - Create a `pipeline.yml` file in the GitHub repo <br> - Define a YAML file and list all steps to execute each step of Machine Learning <br> - Push all files to GitHub <br> - Automate the end-to-end workflow <br> - Update the workflow to automatically push code updates to the main branch | 15 |
| Output Evaluation | - GitHub (link to repository, screenshot of folder structure and executed workflow) <br> - Streamlit on Hugging Face (link to HF space, screenshot of Streamlit app) | 8 |
| Actionable Insights and Recommendations | - Key takeaways for the business | 4 |
| Business Report Quality | - Adhere to the business report checklist | 6 |
| **Total** | | **60** |