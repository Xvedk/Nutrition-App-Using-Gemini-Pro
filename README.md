# Nutrition App Using Gemini Pro

## Overview
The Nutrition App is designed to provide personalized dietary advice and well-being tips by leveraging the advanced capabilities of the Gemini Pro pre-trained model. This application allows users to input their nutritional goals and preferences and receive tailored recommendations that promote healthy eating and lifestyle improvements.

## Project Flow
1. **User Interaction:**
   - Users interact with the UI to enter their dietary goals, preferences, or any other relevant information.
   
2. **Data Transmission:**
   - The user input is collected from the UI and transmitted to the backend using a Google API key.

3. **Model Processing:**
   - The input is forwarded to the Gemini Pro pre-trained model via an API call.
   - The model processes the input and generates personalized nutrition and well-being advice.

4. **Result Display:**
   - The results are returned to the frontend for formatting and display, providing the user with actionable insights.

## Setup Instructions

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Pip (Python package installer)

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/jatinkumarverma/nutrition-app.git
   cd nutrition-app
   ```

2. **Create a Virtual Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**
   Install all required libraries listed in the `requirements.txt` file:
   ```bash
   pip install -r requirements.txt
   ```

### Google API Key Setup

1. **Generate Google API Key:**
   Obtain a Google API key from the Google Cloud Console. Make sure to restrict the API key to your application.

2. **Initialize Google API Key:**
   Set up the Google API key in your application by either:
   - Setting it as an environment variable:
     ```bash
     export GOOGLE_API_KEY='your-api-key'
     ```
   - Including it in your backend configuration.

## Resources

The following resources were used to guide the development of this project:

- **Generative AI Concepts:**
  - NLP: [TutorialsPoint - Natural Language Processing](https://www.tutorialspoint.com/natural_language_processing/index.htm)
  - Generative AI: [Wikipedia - Generative Artificial Intelligence](https://en.wikipedia.org/wiki/Generative_artificial_intelligence)
  
- **Gemini Pro:**
  - [Google - Gemini API Documentation](https://ai.google.dev/gemini-api/docs/get-started/python)
  
- **Streamlit:**
  - [GeeksforGeeks - A Beginner's Guide to Streamlit](https://www.geeksforgeeks.org/a-beginners-guide-to-streamlit/)

## Results
1. 
![OUTPUT1](https://github.com/user-attachments/assets/3882922d-8017-467c-bdeb-00a579fb301b)
2.
![OUTPUT2](https://github.com/user-attachments/assets/191be41f-1831-4aef-9088-cbe589fff8f8)
3.
![OUTPUT3](https://github.com/user-attachments/assets/789f5b3b-313d-464e-96e7-16656dde8ec5)



