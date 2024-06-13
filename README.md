# Password System Evolution Lab

This Flask application demonstrates the evolution of password systems by providing different versions of signup and login functionalities.

## Prerequisites

- Python 3
- Flask
- sqlite3
- pyotp
- hashlib
- uuid

## Installation

Clone the repository to your local machine.

## Running the Application

Navigate to the directory containing the script and use the following command:

```bash
python3 password-evolution.py
```

The application will start running on https://0.0.0.0:5000.

## Endpoints

- `/` - A welcome page.
- `/signup/v1` - A signup endpoint using plain text password storage.
- `/login/v1` - A login endpoint corresponding to the first version of signup.
- `/signup/v2` - A signup endpoint using hashed password storage.
- `/login/v2` - A login endpoint corresponding to the second version of signup.

## Built With

- Flask - The web framework used.
- sqlite3 - Database engine.
- hashlib - SHA-256 Hashing Algorithm.
