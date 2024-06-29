
https://github.com/SomnathBiswas/Debug-Detectives/assets/108716703/c3016d1b-7ca9-45f5-b96a-c80d8402313f
# Medify 🌐🩺 | An AI Powered Web Based Healthcare Chatbot

## Overview ℹ️
Medify is a web-based healthcare chatbot designed to assist users with their medical needs. It checks and predicts diseases, analyzes symptoms, and suggests appropriate actions. It helps users find nearby hospitals and provides consultations with doctors. Medify aims to make healthcare more accessible and efficient by leveraging technology to provide reliable medical advice and support. The project's goal is to enhance user experience by predicting diseases based on symptoms, checking specific disease symptoms, finding nearby hospitals based on GPS location, and facilitating doctor consultations.

## Setup Instructions 🛠️

### Prerequisites ✅

Before you begin, ensure you have the following installed on your device:

- Python (version 3.6 or higher) 🐍
- Git 📦
- pip (Python package installer) 📦

### Installation Steps 🚀

1. **Clone the Repository**

    Open your terminal and clone the repository:

    ```bash
    git clone https://github.com/yourusername/medify.git
    cd medify
    ```

2. **Set Up a Virtual Environment**

    It's recommended to use a virtual environment to manage your dependencies. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install Dependencies**

    Install the necessary Python packages using pip:

    ```bash
    pip install Flask
    pip install Flask-SQLAlchemy
    pip install pandas
    pip install scikit-learn
    pip install joblib
    pip install openpyxl
    pip install duckduckgo-search
    ```

    To install all dependencies at once, you can create a `requirements.txt` file with the following content:

    ```
    Flask
    Flask-SQLAlchemy
    pandas
    scikit-learn
    joblib
    openpyxl
    duckduckgo-search
    ```

    Then run:

    ```bash
    pip install -r requirements.txt
    ```

### Running the Flask Server 🌐

1. **Set Environment Variables**

    Set the `FLASK_APP` environment variable to specify the entry point of your application. You can do this in your terminal:

    ```bash
    export FLASK_APP=app.py  # On Windows, use `set FLASK_APP=app.py`
    ```

2. **Run the Flask Server**

    Start the Flask development server by running:

    ```bash
    flask run
    ```

    The server will start, and you can access your application in your web browser at [http://127.0.0.1:5000](http://127.0.0.1:5000).

---

Feel free to customize these instructions based on your specific setup and configuration needs. If you encounter a


## Features 🚀
- **Disease Prediction:** Medify utilizes advanced algorithms to analyze user-entered symptoms and predict potential diseases or health conditions.
- **Symptom Assessment:** Users can input their symptoms, and Medify provides assessments and recommendations based on severity and nature.
- **Doctor Consultation:** Medify connects users with healthcare professionals for remote consultations, ensuring convenient access to medical advice.

## Getting Started 🏃‍♂️💻
To use Medify, simply navigate to the web-based interface and start interacting with the chatbot. No installation or additional software is required. Users can input their symptoms, ask questions, and receive personalized recommendations and guidance.

## Technologies Used 🛠️
- **Artificial Intelligence:** Medify employs state-of-the-art AI technologies to understand user inputs, analyze symptoms, and provide accurate responses.
- **Web Development:** The chatbot interface is built using modern web technologies such as HTML, CSS, and JavaScript, ensuring a seamless user experience across devices.
- **Backend Infrastructure:** Medify’s backend handles user requests, data processing, and interfaces such as doctor consultations.
- **Data Privacy and Security:** Medify prioritizes data privacy and security, implementing robust measures to protect user information and comply with regulations.

## Flow Diagrams ✏️


![Beige Colorful Minimal Flowchart Infographic Graph](https://github.com/SomnathBiswas/Debug-Detectives/assets/108716703/a9a0826a-12a4-4c7a-a60e-1cdc3c0e38a4)

![Beige Colorful Minimal Flowchart Infographic Graph (1)](https://github.com/SomnathBiswas/Debug-Detectives/assets/108716703/121dd2fd-1fe4-43de-8a97-c542a3aa966d)

## Demo Video 

https://github.com/SomnathBiswas/Debug-Detectives/assets/108716703/94998ea3-03ae-4c14-964e-11fefb3a4d5b






