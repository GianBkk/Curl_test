# Abfrage My SQL

Abfrage aller Tasks 
``` sql

SELECT * FROM todos.todo_items;

Abfrage aller offenen Tasks 
SELECT * FROM todo_items WHERE completed = false

Setzen eines 'unerledigten' Tasks auf 'erledigt'-
UPDATE todo_items SET completed = true WHERE id = 'ID'

Erstellen eines neuen Tasks 
INSERT INTO todo_items (name, completed) VALUES (Waschen, false)

Löschen Eines Tasks
DELETE FROM todo_items WHERE name = 'Waschen'
```

