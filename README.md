
1. `curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.4.1/docker-compose.yaml'`
2. `mkdir ./dags ./logs ./plugins`
3. `touch .env`
4. `echo -e "AIRFLOW_UID=$(id -u)" > .env`
5. `docker-compose up airflow-init`
6. `docker-compose up`
7. `localhost::8080/home`