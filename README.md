# Outlier Detection API
This project provides a RESTful API for detecting outliers using a machine learning classifier. The API is built with FastAPI and utilizes a pre-trained classifier model loaded with pickle.

## Project Structure
main.py: The main FastAPI application file. It defines the API endpoints and handles predictions.
meta.py: Contains the Pydantic model for request validation.
outlier.pkl: The pre-trained classifier model used for detecting outliers.
Installation
To get started, you'll need Python 3.7+ and pip. First, clone the repository:


#### curl {
  "X1": 1.5,
  "X2": 2.5
}'

### Example response:

json
Copy code
{
  "prediction": "Not a Outlier"
}
### Files
main.py: Contains the FastAPI application and prediction logic.
meta.py: Defines the Pydantic model var_data used for request validation.
outlier.pkl: Serialized classifier model for outlier detection.
Model
The classifier model used for detecting outliers is a pre-trained model serialized with pickle. Ensure that outlier.pkl is in the correct directory for the application to load the model successfully.

### Development
To contribute to this project, fork the repository, create a new branch, and submit a pull request with your changes.



### Acknowledgements
FastAPI for building high-performance APIs.
scikit-learn for providing powerful machine learning tools.
