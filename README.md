# MyProject

## dental clinic

ישויות: רופאים,תורים,מטופלים
### מיפוי routs לרופאים:
שליפת רשימת רופאים:
GET http://MyProject.com/Dentists
שליפת רופא מתוך רשימת רופאים לפי מספר מזהה:
GET http://MyProject.com/Dentists/1
הוספת רופא לרשימה:
POST http://MyProject.com/Dentists
מחיקת רופא מהרשימה:
DELETE http://MyProject.com/Dentists/2
### מיפוי routs לתורים:
שליפת רשימת תורים:
GET http://MyProject.com/queues
שליפת תור לפי מספר מזהה:
GET http://MyProject.com/queues/1
הוספת תור:
POST http://MyProject.com/queues
עדכון תור:
PUT http://MyProject.com/queues
עדכון תור לפי מספר מזהה:
PUT http://MyProject.com/queues/2
מחיקת תור:
DELETE http://MyProject.com/queues/4
### מיפוי routs למטופלים:
שליפת רשימת מטופלים:
GET http://MyProject.com/Patients
שליפת פרטי מטופל לפי מספר מזהה:
GET http://MyProject.com/Patients/3
הוספת מטופל לרשימה:
POST http://MyProject.com/Patients
מחיקת מטופל מהרשימה:
DELETE http://MyProject.com/Patients/1
עדכון פרטי מטופל לפי מספר מזהה:
PUT http://MyProject.com/Patients/6
