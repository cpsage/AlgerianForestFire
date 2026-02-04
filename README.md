🚀 Project Title & Tagline

Fire Weather Index (FWI) Prediction System 🌪️ A web-based application for predicting fire weather index using machine learning
📖 Description

The Fire Weather Index (FWI) Prediction System is a web-based application designed to predict the fire weather index using machine learning algorithms. The application allows users to input temperature and other relevant data to receive a predicted FWI value. The system is built using Flask, a popular Python web framework, and utilizes scikit-learn for machine learning tasks.

The application consists of two main pages: a homepage that welcomes users and a login page that allows users to input data and receive predictions. The login page features a simple form that accepts temperature and other relevant data, which is then processed by the machine learning model to generate a predicted FWI value. The application also includes a backend API that handles data processing and prediction tasks.

The FWI Prediction System has numerous applications in wildland fire management, including predicting fire danger, identifying high-risk areas, and optimizing resource allocation. By providing a user-friendly and accurate prediction system, the application aims to support fire managers and emergency responders in their critical work. The application is designed to be scalable, flexible, and easy to maintain, making it an ideal solution for a wide range of users.
✨ Features

Here are some of the key features of the FWI Prediction System:

    User-friendly interface: The application features a simple and intuitive interface that allows users to easily input data and receive predictions.
    Machine learning-based prediction: The application utilizes scikit-learn to build and train machine learning models that predict FWI values based on user-input data.
    Data processing and storage: The application includes a backend API that handles data processing and storage tasks, ensuring that user data is secure and easily accessible.
    Scalability: The application is designed to be scalable, making it easy to add new features and users as needed.
    Flexibility: The application is built using Flask, a flexible and modular framework that allows for easy customization and extension.
    Security: The application includes robust security measures to protect user data and prevent unauthorized access.
    Real-time predictions: The application provides real-time predictions, allowing users to quickly and easily receive FWI values.
    Data visualization: The application includes data visualization tools, making it easy for users to understand and interpret prediction results.

🧰 Tech Stack Table

| Category | Technology | | --- | --- | | Frontend | HTML | | Backend | Flask, Python, scikit-learn | | Database | Pandas, NumPy | | Tools | Pickle, StandardScaler |
📁 Project Structure

The project is organized into the following folders:

    app: This folder contains the Flask application code, including the application.py file.
    templates: This folder contains HTML templates for the application, including the home.html and index.html files.
    static: This folder contains static assets, such as CSS and JavaScript files.
    models: This folder contains machine learning models and data processing code.
    data: This folder contains user data and other relevant data used by the application.

⚙️ How to Run

To run the application, follow these steps:

    Setup: Install the required dependencies, including Flask, scikit-learn, and Pandas.
    Environment: Create a new virtual environment using python -m venv env.
    Build: Build the application by running python application.py.
    Deploy: Deploy the application to a production environment, such as a cloud platform or containerization service.

🧪 Testing Instructions

To test the application, follow these steps:

    Unit testing: Run unit tests using python -m unittest.
    Integration testing: Run integration tests using python -m pytest.
    User testing: Test the application manually by inputting data and verifying prediction results.

📦 API Reference

The application includes a RESTful API that provides access to prediction data and other relevant information. The API is documented using Swagger and includes the following endpoints:

    /predict: Predict FWI value based on user-input data.
    /data: Retrieve user data and other relevant information.

👤 Author

The FWI Prediction System was developed by Rishi Sharma.
