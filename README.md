Go to postman> click on import > paste the below curl for testing the endpoint

curl --location 'http://localhost:8081/login' \
--header 'Content-Type: application/json' \
--data '{"username":"admin", "password":"admin"}'
