Get the token

curl -X POST 'http://localhost:8080/login?username=test&password=test'

Pass the token, always starts with ey
curl -X GET http://localhost:8080/hello -H 'Content-Type: application/json' -H 'Authorization: Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1c2VyIiwidXNlciI6InVzZXIiLCJleHAiOjE2NTQ3MTIyNjZ9.THHGPzholo1G3tYkWMR9phqAySfcO6vHI4ZBsDuDxdY'
