# Vet Clinic Database Project – CISC 450

This is my database design project for **CISC 450 (Database Design I)** at the University of St. Thomas. The goal was to design a database for a veterinary clinic, document the requirements, and build a small Flask app on top of the schema.

---

## What’s in here

- `schema.pdf`  
  Final ERD / schema for the vet clinic database.

- `annotatedRequirements.pdf`  
  Annotated requirements document describing what the system needs to do.

- `reflection.pdf`  
  My reflection on the project and what I learned.

- `AIprompts.pdf`  
  Prompts I used when working with AI during the project.

- `source.txt`  
  Source information for the data / scenario.

- `code/`  
  The actual Flask app:
  - `app.py`, `alchemyBase.py`, `DBproj.db`
  - `templates/` with the HTML views

---

## How to run the app

1. Clone this repo and go into it:

       git clone https://github.com/akoenen/db-vet-clinic.git
       cd db-vet-clinic/code

2. Install the Python packages (Flask, SQLAlchemy, etc.):

       pip3 install flask sqlalchemy

3. Run the app:

       python3 app.py

4. Open `http://localhost:5000` in a browser.

---

## My role

- Helped design the schema and think through how the clinic’s data should be organized  
- Worked with the team on the Flask app and templates  
- Wrote reflection and documentation pieces included in the PDFs  

---

## Why I picked this project

This project shows the full database side of my work: requirements, schema design, documentation, and a working app on top of it. It’s a good example of how I think about structure and data before writing code.
