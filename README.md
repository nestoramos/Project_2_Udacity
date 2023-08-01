# Disaster Response Pipeline Project

### Summary and Motivation
This second project has worked to development an interesting model to predict best categories about the message that arise from some catastrophes. This will be helfup to achieve the appropiate help for each situation.

### Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database, don't forget to run with the proper code, for example:
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run your web app: `python run.py`

### Documents

- dissaster_messages: A csv file that containts, the message, genre and categories for this messages, you can find in the data folder
- Process_data.py, file where the data is process to clean and transform to the propert form, you can find in the data folder
- train_classifier.py, file where the model was build, you can find in models folder
- run.py, is the master file, from this document the page is created along with templates, all in the app folder


