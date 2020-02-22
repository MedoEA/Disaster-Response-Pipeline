
## Disaster Response Pipeline

I used the data pipeline abilties learned to analyze disaster dataset from Figure Eight to build a model for an API that classifies disaster  messages.I create a machine learning pipeline to categorize these activities so that I can send the messages to the ideal disaster remedy agency.

### Table of Contents

1. Instructions
2. File Descriptions
3. Licensing, Authors, and Acknowledgements

### Instructions:

1. Run the following commands in the project's root directory to set up your database and model.

  * To run ETL pipeline that cleans data and stores in database:
    * "python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db"
  * To run ML pipeline that trains classifier and saves:
    * "python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl"
2. Run the following command in the app's directory to run your web app.
  * "python run.py"
3. Go to
  * http://0.0.0.0:3001/

### File Descriptions:

* process_data.py: A ETL Pipeline
* train_classifier.py: A Machine Learning Pipeline
* run.py: A Flask Web App that visualizes the results

### Licensing, Authors, Acknowledgements

Must give credit to Udacity and Figure Eight for the dataset.


```python

```
