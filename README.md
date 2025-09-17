# sihsafhh
SIHSAM Tourist Portal - Flask Backend

How to run:
1) Open PowerShell and run:
   cd "C:\Users\Samuel\OneDrive\Desktop\sihsam-flask"
   py -m venv .venv
   .\.venv\Scripts\Activate.ps1
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   python app.py

Login API:
- POST http://127.0.0.1:5000/api/auth/login
  body: { "email": string, "password": string }

Sample users:
- alice@example.com / password123
- bob@example.com / welcome123

Front-end integration:
- tourist-login.html is already wired to call the endpoint and will redirect to tourist-dashboard.html on success.
