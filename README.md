# End to End ML Deployment Project-Boston House Pricing Prediction

This project is an end-to-end deployment of a machine learning model for predicting the prices of houses in Boston. The model has been developed using the Boston Housing dataset and the scikit-learn library. The model has been deployed on Heroku using Github Actions.

## Software and Tools Requirements

1. [GithubAccount](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)
5. GitHub Actions
6. Scikit-learn
7. [Postman](https://www.postman.com/)


Create a New Environment
```
python -m venv %name of virtual environment
```

Activating New Environment
```
then activate after going to venv folder then ./Scripts/activate
myvenv/Scripts/activate
```


## Model Development:

The model was developed using the Boston Housing dataset, which is a standard machine learning dataset for regression problems. The dataset contains 506 rows and 14 columns, with the target variable being the median value of owner-occupied homes in $1000's.

The model was developed using the scikit-learn library, which is a popular machine learning library for Python. The following steps were taken to develop the model:

1. Data Preprocessing: The data was preprocessed to handle missing values, outliers, and to normalize the data.

2. Feature Engineering: The data was split into features and target variables. The features were used to train the model.

3. Model Selection: A Random Forest Regressor was selected as the final model. The model was trained on the training data and evaluated on the validation data.

4. Model Evaluation: The model was evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## Deployment:

The model was deployed on Heroku, which is a cloud platform that allows for the deployment of web applications. The following steps were taken to deploy the model:

1. Creating a Heroku Account: A Heroku account was created to host the application.

2. Setting up the Application: A new Heroku application was created and the necessary dependencies were installed.

3. Deploying the Model: The model was deployed to Heroku using Github Actions. The model was trained on the Boston Housing dataset and the predictions were made using the Heroku API.

4. Testing the Model: The model was tested using Postman, which is a tool for testing APIs. The predictions were compared to the actual values and the accuracy of the model was verified.

## Conclusion:

The end-to-end ML deployment project was a success, with the model being deployed on Heroku and being able to make accurate predictions. The deployment of the model on Heroku allows for easy access to the model by users, making it possible to integrate the model into real-world applications.