
# Install dependencies. Run following command

 ```bash
pip install -r requirements.txt
```
# Setup with Docker

Docker and docker-compose need to be installed. To start the services run

`docker-compose up --build`

Test running jupyter server by accessing `http://localhost:3000/` with password `data`.
Test running database by accessing the database via `psql -h 0.0.0.0 -p 5430 -U data_engineer test_db`.
