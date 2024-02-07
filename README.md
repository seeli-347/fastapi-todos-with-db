# FastApi Todos mit MySQL-Datenbank

### Ziel: Die Applikation soll in Container verpackt werden. 
- api
- db
- dbtool

#### Startbefehl CMD der API

"uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8000"

### Aufgabe 1: Erstelle 
- Dockerfile
- .dockerignore

Starte dann die Applikation mit docker run auf Port 8000.
Die Applikation verwendet SQLight als Datenbank im Hintergrund.
Gehe auf localhost:8000/docs und teste die API
