# Python Data Engineer Code Challenge

This project is part of a Python data engineering challenge. The main objective is to perform data analysis and visualizations using Python and PostgreSQL as a database.

## Requirements

1. **Install Python 3.10**: Follow the instructions at [Python Downloads](https://www.python.org/downloads/).

2. **Install Jupyter Notebooks**: Follow the instructions at [Jupyter Install](https://jupyter.org/install).

3. **Install Git**: Follow the instructions at [Git Installation](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).

4. **Install Docker**: Follow the instructions at [Docker Installation](https://docs.docker.com/engine/getstarted/step_one/#step-2-install-docker).

### You will need Docker to run PostgreSQL database in a container.

## Running the Project
1. Clone this repository on your local machine: git clone https://github.com/ImBetterThanYesterday/data_engineer_workshop.git
2. Set up your virtual environment (optional but recommended) and activate the environment.
3. Install the required libraries:
   ```bash
   pip install pandas numpy psycopg2 psycopg2 sqlalchemy json
4. Run the PostgreSQL database in a Docker container using the following command:
   ````bash
   sudo docker run -d --name=postgres -p 5432:5432 -v postgres-volume:/var/lib/postgresql/data -e POSTGRES_PASSWORD=mysecretpass postgres
5. Create a db_config.json file (in the same folder) with the PostgreSQL database connection parameters:
    {
    "host": "localhost",          
    "port": "5435",               
    "database": "postgres",       
    "user": "postgres",           
    "password": "mysecretpass"
    }
6. Run the project








   
