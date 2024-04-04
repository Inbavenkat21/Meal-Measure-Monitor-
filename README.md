# MealMeasureMonitor-Project
Meal Measure Monitor
This is a health management app that utilizes generative AI to analyze images of food items, calculate total calories, and provide details of each food item with their respective calorie intake.

Getting Started
Prerequisites
Make sure you have Python installed on your system. You can download it from python.org.

Installation
Clone this repository to your local machine.
Navigate to the project directory.
Install the required dependencies by running:

pip install -r requirements.txt

Usage
Ensure you have set up the necessary environment variables. You may need to obtain an API key from Google for the Gemini Pro Vision API.
Run the Streamlit app by executing the following command in your terminal:
arduino

streamlit run app.py

Once the app is running, you can input a prompt and upload an image containing food items.
Click the "Tell me the total calories" button to analyze the image and receive the total calories along with details of each food item.
Built With
Streamlit - The web framework used for building interactive web applications with Python.
Google Generative AI - Utilized for generative AI capabilities, specifically the Gemini Pro Vision API.
Pillow (PIL) - Python Imaging Library used for opening, manipulating, and saving many different image file formats.
