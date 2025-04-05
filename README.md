# exam-group-L-api

Leader: Diosana

Features:
POST/exams : Bacalan
GET/exams  : Nacar
PUT/exams  : Nacar
 

#Install indepencies

npm init -y
npm install
npm install express
npm install express body-parser


test the code

GET /exam-group:
URL: http://localhost:3000/exam-group

Response: 
{
  "message": "Group L API"
}

GET /exams:
URL: http://localhost:3000/exams

Response: All list of exams.

POST /exams:
URL: http://localhost:3000/exams

Body (JSON):
{
  "name": "Filipino Exam",
  "date": "2025-04-05"
}

Response:

{
  "name": "Filipino Exam",
  "date": "2025-04-05",
  "id": 5
}

PUT /exams/{id}:
URL: http://localhost:3000/exams/1

Body (JSON):
{
  "name": "Science",
  "date": "2025-04-05"
}

Response:
{
  "id": 1,
  "name": "Science",
  "date": "2025-04-05"
}
	
