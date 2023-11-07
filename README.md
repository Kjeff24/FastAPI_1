# FASTAPI WITH POSTGRES
## Installation

To install the project, you need to have Python 3 and pip installed on your system. Then, follow these steps:

- Clone this repository: 
[FastAPI_1](https://github.com/Kjeff24/FastAPI_1.git)
- Create a virtual environment: 
```
python -m venv venv
```
- Activate the virtual environment: 
```
`source venv/bin/activate` (on Linux/Mac) or `venv\Scripts\activate` (on Windows)
```
- Install the required dependencies: 
```
pip install -r requirements.txt
```

## Usage

- To run the project, setup the database connection strings. You can use a `.env` file to store them, for example 
```
DB_USER=postgres
DB_PASSWORD=mypassword
DB_HOST=localhost
DB_PORT=5432
DB_NAME=fastapi
```
Or directly change the url in `database.py`. For example 
```
SQLALCHEMY_DATABASE_URL = f"postgresql://postgres:mypassword@localhost/fastapi"
```