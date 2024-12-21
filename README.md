# Food-Delivery-ChatBot

A chatbot application built with Dialogflow (NLP) and FastAPI for food ordering and delivery management. The chatbot interacts with users seamlessly to take orders, provide real-time tracking, and manage orders using MySQL as the backend database.
__________________________________________________________________________________

# Overview
The Food Delivery Chatbot simplifies food ordering processes by integrating natural language processing with an easy-to-use API. It ensures a smooth experience for users to interact with the chatbot, making ordering food more efficient and accessible.
__________________________________________________________________________________


# Objectives
Enable a seamless food ordering experience through natural language interaction.
Provide real-time order tracking for customers.
Manage orders efficiently with MySQL for back-end storage.
Offer a simple and responsive user interface.
__________________________________________________________________________________


# Tech Stack
Programming Language: Python
Frameworks: FastAPI, Dialogflow
Frontend: HTML, CSS
Database: MySQL
Tools: Dialogflow for NLP integration
__________________________________________________________________________________


# Methodology
User Interaction: The user interacts with the chatbot via the web interface or messaging platform.
Natural Language Processing: Dialogflow processes user queries and generates appropriate responses.
Order Management: The chatbot integrates with the backend (via FastAPI) to store and manage orders in MySQL.
Real-Time Updates: The chatbot provides real-time tracking of food orders.
__________________________________________________________________________________


# Features
Conversational AI for food ordering.
Real-time order tracking.
MySQL database for order management and storage.
User-friendly interface with HTML and CSS.
Flexible deployment options.
__________________________________________________________________________________


# Setup and Installation
Clone the Repository:

git clone https://github.com/srushti207/Food-Delivery-ChatBot.git
cd Food-Delivery-ChatBot

pip install -r requirements.txt
Set Up the MySQL Database:

Create a MySQL database for order management.
Update the database connection settings in the project configuration file.
Run the Application:

uvicorn main:app --reload
Access the Application: Open your web browser and go to http://127.0.0.1:8000.
__________________________________________________________________________________


# Usage
Start the chatbot application.
Interact with the chatbot via the web interface.
Place food orders by providing inputs through natural language.
Track the status of your order in real-time.
__________________________________________________________________________________


# Directory Structure
arduino
Copy code
Food-Delivery-ChatBot/
├── main.py
├── app/
│   ├── models.py
│   ├── views.py
│   ├── database.py
│   ├── routers/
│   │   ├── chatbot.py
│   │   └── orders.py
│   ├── templates/
│   │   └── ...
│   ├── static/
│   │   └── ...
├── requirements.txt
├── README.md
└── config/
    └── database_config.py
