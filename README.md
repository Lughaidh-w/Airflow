# Airflow Docker Image
### Running image
docker compose up

### Interacting with API
#### Dags
curl -X GET --user "airflow:airflow" "http://localhost:8080/api/v1/dags"
