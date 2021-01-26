# Abfrage in Curl

Abfrage aller Tasks
````bash
http localhost:3000/tasks
````

Abfrage aller offenen Tasks
````bash
````

Setzen eines 'unerledigten' Tasks auf 'erledigt'
````bash
curl -X PUT -H "Content-Type: application/json" -d '{ "name": "Huehner Fuettern", "completed": true }' http localhost:3000/items/ID
````


Erstellen eines neuen Tasks 
````bash
curl -X POST -H "Content-Type: application/json" -d 'name=Waschen' -d 'completed=false' http localhost:3000/tasks
````

Löschen eines Tasks 
````bash
curl -X DELETE http://localhost:3000/tasks/ID
````