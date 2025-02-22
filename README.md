# backend-service-with-fastapi-and-firestore

Follow this tutorial link

https://medium.com/@judydev/create-a-backend-service-with-fastapi-and-firestore-88f327bacfcb

# Setup & Installation

git clone https://github.com/cynthia-natalie/backend-service-with-fastapi-and-firestore.git
cd backend-service-with-fastapi-and-firestore
pip install -r requirements.txt

run fastapi app:
uvicorn app.app:app --reload

fetch cities:
curl -X GET "http://127.0.0.1:8000/cities" -H "accept: application/json"