# Airbnb-Price-Prediction 

The purpose of this project is to predict the price of Airbnb rentals based on various features of the properties listed on the platform. The code in this repository is written in Python and uses several machine learning algorithms to train and test a predictive model.

# Dataset

The Airbnb dataset includes 29 variables and 74111 observations. The variables which are listed below are the final variables in the dataset.

 - Room Type: This includes the category of space available for rent. 

 - Property Type: This defines the kind of housing the property.

 - City: It is the name of the city/town where our property is located.

 - Latitude: It is the exact coordinates where our property is located.

 - Longitude: It is the exact coordinates where our property is located,

 - Amenities: These are the various features available at the rental that increase the desirability of the rental

 - Number of Reviews: It is the number of testimonials that the previous customers had provided after using the property.

 - First Review: It is the date of the very first review from the customer posted.

 - Last Review: It is the date of the latest review from the customer posted.

 - Review Score Rating: It is the collective score of all the previous reviews posted.

 - Thumbnail URL: It is the hyperlink of the display picture of the property available online.

 - zip code: It is the pin code of the location. 

 - Host Profile pic: It is the presence of the actual picture of the owner/host that owns the property.

 - Host Identity Verified: It tells if the owner/host is a real person verified by the authorities.

 - Host Response rate: It is the probability of the owner/host responding to your message if you decide to send one.

 - Host Since: It is the time period since when he had been the host.

 - Name: It is the name of the property.

 - Neighborhood: It is the local street/town place that the neighborhood is located in.

 - Accommodates The number of people that could comfortably use the rental.

 - Bathrooms: It indicates the number of bathrooms available on the rental.

 - Cancellation Policy: This tells whether the incentive that was submitted to confirm the rental will be reliably sent back in case of cancellation.

 - Cleaning Fee: It is the basic maintenance fee charged along with the rental fee.

 - Instant Bookable: It indicates how much delay it takes to confirm the rental for your use or if it is bookable at the last moment.

 - Review Score Rating: Gives the data on the experience of previous users.

 - Description: It is a very short but concise overview of the rental property.

 - Bedrooms: It indicates the number of bedrooms available on the rental.

 - Beds: It indicates the number of total beds available on the rental.

 - Bed Type: It is the type of bed available in the rental. 

 - Log Price: It refers to the natural logarithm of a given price. It is calculated by taking the logarithm of the price and can be used to normalize price data and make it easier to analyze.

# Installation

To run this code, you need to have Python installed on your machine. Additionally, you will need to install several Python packages, including:

 - Numpy

 - Pandas

 - Seaborn

 - Matplotlib

 - Scikit-learn

 - Catboost

 - Xgboost

You can install these packages using the pip package manager.

# Usage

To use this Airbnb analysis project, follow these steps:

→ Clone the project repository to your local machine.

→ Install the required dependencies listed in the requirements.txt file. 

→ You can do this by running the following command in your terminal:

pip install -r requirements.txt

→ Open the Jupyter notebook Airbnb_Analysis.ipynb in Jupyter Notebook or Jupyter Lab.

→ Follow the step-by-step analysis in the notebook, running each cell to execute the code and generate the output.


# Model Training and Evaluation

The final section of the code trains several machine learning models on the preprocessed data and evaluates their performance using various metrics such as mean squared error and R-squared. The models used in this project include:

Linear Regression

Polynomial Regression

CatBoost Regressor

Gradient Boosting Regressor

XGBoost Regressor

Random Forest Regressor

The code uses a grid search algorithm to optimize the hyperparameters of each model and cross-validation to evaluate the performance of each model. Finally, the code selects the best performing model and uses it to predict the prices of new Airbnb listings.

Here is the Model Working Flow

![image](https://user-images.githubusercontent.com/101493756/230591497-f8b94043-ff34-47ba-ac54-16b99771d27c.png)

# Contributing

We welcome contributions from the community! If you have any ideas or suggestions for improving the project, please feel free to create an issue or submit a pull request.

# Acknowledgements

This project was inspired by the Kaggle dataset on AirBNB Price Prediction and the corresponding competition. We also acknowledge the open-source Python libraries used in this project and their contributors.
