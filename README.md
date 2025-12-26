# Elasticsearch Search Tutorial

- Start the containers
  `docker compose up -d`
- Create a virtual enviornment
  `py -m venv .venv`
- Activate the virtual environment
  `source .venv/bin/activate` or in WLS `.venv\Scripts\activate`
- Intsall the dependencies
  `pip install -r requirements.txt`
- Run the Project
  `flask run`
- Visit ` http://127.0.0.1:5001/`
- When you are done with containers, stop them `docker compose down`
