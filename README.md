PSIT Student Toolkit

A web-based student utility built with Streamlit that connects to the PSIT ERP system and provides essential academic insights in a single dashboard.
This application helps students monitor attendance, estimate risk, plan bunks responsibly, and view their daily timetable.


---

Overview

PSIT Student Toolkit is designed to simplify student decision-making by automating key ERP checks and presenting them in a clean, interactive interface.

The application securely logs into the ERP session, fetches relevant data, and displays:

Attendance summary

Current attendance fine (Security Deposit)

Lectures required to reach 90% attendance

Maximum lectures that can be safely bunked

Today's timetable



---

Features

Attendance Dashboard

Total lectures conducted

Present and absent count

Attendance percentage (without PF)

Real-time fine fetched directly from ERP


90% Requirement Calculator

Determines the number of additional lectures required to reach the mandatory 90% attendance.

Safe Bunk Calculator

Calculates how many future lectures can be missed while maintaining at least 90% attendance.

Today's Timetable

Automatically detects the current day

Extracts the highlighted timetable row from ERP

Displays lecture-wise details



---

Technology Stack

Python

Streamlit

Requests

BeautifulSoup (bs4)

Pandas



---

Installation (Local Setup)

1. Clone the repository



git clone https://github.com/Adaptoid0s981/erp-test-0.1.git
cd erp-test-0.1

2. (Optional) Create a virtual environment



Windows:

python -m venv venv
venv\Scripts\activate

Linux / macOS:

python3 -m venv venv
source venv/bin/activate

3. Install dependencies



pip install -r requirements.txt

4. Run the application



streamlit run app.py


---

Deployment

This project can be deployed using Streamlit Cloud.

Steps:

1. Push the repository to GitHub


2. Go to Streamlit Cloud


3. Create a new app


4. Select the repository and branch


5. Set the main file as:



app.py

Ensure the repository contains:

app.py
requirements.txt
README.md


---

Security & Privacy

ERP credentials are not stored.

Authentication is session-based and temporary.

No user data is saved, logged, or shared.



---

Project Structure

.
├── app.py
├── requirements.txt
└── README.md


---

Disclaimer

This is an unofficial student utility and is not affiliated with PSIT.
Use responsibly and do not share your ERP credentials with untrusted sources.


---

Author

Developed as a productivity tool for PSIT students to manage attendance and schedule planning efficiently.
