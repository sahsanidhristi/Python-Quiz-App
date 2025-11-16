AI quizzer app
AI Quizzer is a simple quiz application built using **FastAPI**. It provides a set of quiz questions, accepts user answers, evaluates the result, and sends the result to the user's email.


Working of project:
1. login by using credentials 
2. attmempt the quiz
3. and write the email id to receive the score on the id
4. receive email for same.


LOGIN CREDENTIALS:
my credinals for username: xyz and password is xyz@2002, and they are hardcoded into code not dynamic 
So use this for username login 

Features of my project:
- JWT token-based authentication
- Get quiz questions
- Submit answers and receive evaluation
- Automatic result email to the user
- Clean modular code with Pydantic models

Running the project
1.pip install -r requirements.txt
2. in one terminal run this command: uvicorn main:app --reload(http://127.0.0.1:8000/)
3. For frontend running streamlit in second terminal : streamlit run client.py(http://localhost:8501)
"# Python-Quiz-App" 
