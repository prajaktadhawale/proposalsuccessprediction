# proposalsuccessprediction

## Setup

### Prerequisites

Make sure you have Python installed. It's recommended to use a virtual environment to manage dependencies.

### Installation

1. **Clone the repository:**
   ```sh
   git clone git@gitlab.com:username/grant-application-success-prediction.git
   cd grant-application-success-prediction

2. **Create a virtual environment (optional but recommended):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. **Adding the Dataset Section**

Add a section that explains where to find the dataset and how to download it:

## Dataset

The dataset used in this project can be found on Kaggle: [Unimelb Grant Application Success Prediction](https://www.kaggle.com/c/unimelb/data).

### Download the Dataset

1. Go to the [dataset page](https://www.kaggle.com/c/unimelb/data).
2. Sign in with your Kaggle account.
3. Download the dataset files and place them in the `data/` directory of this project.

The dataset contains historical grant application data, including features such as applicant details, project summary, requested amount, etc.

## Project Details
### Notebooks
- notebooks/data_preprocessing.ipynb: Contains the data preprocessing steps, including handling missing values, encoding    categorical features, and scaling numerical features.
- notebooks/eda.ipynb: Contains exploratory data analysis (EDA), including visualizations and initial insights from the    dataset.
- notebooks/model_training.ipynb: Contains the model training, evaluation, and tuning steps for various machine learning    models.

## Results

1. Logistic Regression Performance:
   Accuracy: 0.7618
   Precision: 0.7390
   Recall: 0.7380
   F1 Score: 0.7385
2. Random Forest Performance:
   Accuracy: 0.8404
   Precision: 0.8299
   Recall: 0.8174
   F1 Score: 0.8236
3. Support Vector Machine Performance:
   Accuracy: 0.8238
   Precision: 0.8142
   Recall: 0.7947
   F1 Score: 0.8043
4. Neural Network Performance:
   Accuracy: 0.7956
   Precision: 0.7690
   Recall: 0.7884
   F1 Score: 0.7786
 
 ### Feature Importance
The top 20 most important features identified by the Random Forest model are:

## Contributing

If you would like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Contact

If you have any questions or suggestions, feel free to reach out at prajaktadhawale29@gmail.com.


















