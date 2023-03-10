# Fake News Detection

This is a Flask app for detecting fake news using a machine learning model.

## Installation

1.  Clone the repository to your local machine:

    bashCopy code

    `git clone https://github.com/ayushgpt01/news-detection.git`

2.  Navigate to the directory where you have cloned the repository:

    bashCopy code

    `cd news-detection`

3.  Create a virtual environment:

    Copy code

    `python -m venv venv`

4.  Activate the virtual environment:

    bashCopy code

    `source venv/bin/activate`

    Note: If you're using Windows, replace `source venv/bin/activate` with `venv\Scripts\activate`.

5.  Install the required packages:

    Copy code

    `pip install -r requirements.txt`

## Usage

1.  Run the Flask app:

    Copy code

    `python Fake_News_Det.py`

2.  Once the Flask app is running, you can access it by opening a web browser and going to `http://localhost:5000/`.
3.  Enter a news article in the text box and click the "Check" button to detect whether it's real or fake.

## Credits

The machine learning model used in this app is based on the [Fake News Detection dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) from Kaggle.
