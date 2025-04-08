# Expense-Management-System
This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.

#Project Structure
frontend/: Contains the Streamlit application code.
backend/: Contains the FastAPI backend server code.
tests/: Contains the test cases for both frontend and backend.
requirements.txt: Lists the required Python packages.
README.md: Provides an overview and instructions for the project.

Setup Instructions
Clone the repository:
git clone https://github.comTanmoy9563/expense-management-system.git
cd expense-management-system

Install dependencies::
 pip install -r requirements.txt

Run the FastAPI server::
 uvicorn server.server:app --reload
Run the Streamlit app::
 streamlit run frontend/app.py
