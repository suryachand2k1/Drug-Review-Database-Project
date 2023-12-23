# Drug Review Database Project

## Overview
This project aims to create a comprehensive database of drug reviews, offering insights into user experiences, effectiveness, and satisfaction. Utilizing advanced data analysis and machine learning techniques, the project analyzes reviews to extract meaningful patterns and sentiments, contributing to a better understanding of drug efficacy and user experiences.

## Dataset
- **drugsComTest_raw.csv**:
  - Contains drug reviews, ratings, and related information.
  - Fields: `uniqueID`, `drugName`, `condition`, `review`, `rating`, `date`, `usefulCount`.
  - Usage: Analyzing and extracting insights from user-submitted reviews.

## Web Application (`app.py`)
- Flask-based web interface.
- Features:
  - User interaction for querying the database.
  - Uploading and viewing drug reviews.
- Setup: Flask framework with integration of data processing functionalities.

## Data Analysis (Jupyter Notebooks)
- **notebook.ipynb**, **notebook-updated.ipynb**, **notebook-updates.ipynb**:
  - Perform data preprocessing, analysis, and machine learning model development.
  - Extract sentiment and trends from the review dataset.

## Forms (`forms.py`)
- Defines web forms for user input in the Flask application.
- Streamlines the process of querying and displaying data.

## Dataset Analysis (`categorical_se.csv`)
- Used for additional data analysis and visualization.
- Contains categorized data related to various drugs.

## Project Structure
- `app.py`: Flask application for web interface.
- `forms.py`: Form definitions for Flask application.
- Jupyter Notebooks: For data processing and analysis.
- CSV Files: Core datasets for analysis and model training.

## Setup & Installation
1. Install Python 3.x and Flask.
2. Install dependencies for data analysis and machine learning.
3. Clone the repository.
4. Set up a local or cloud-based server for hosting the Flask application.

## Running the Application
- **Flask App**:
  - Run `python app.py` to start the server.
  - Access the web interface via a web browser.
- **Jupyter Notebooks**:
  - Open notebooks in Jupyter Lab/Notebook for analysis and model training.

## Dependencies
- Python 3.x
- Flask
- Pandas, NumPy, Scikit-learn (for data analysis)
- TensorFlow or PyTorch (for machine learning models, if used)
- Matplotlib, Seaborn (for data visualization)

