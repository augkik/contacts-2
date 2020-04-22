# contacts-2
Web service with contacts ant a list of their borrowed books from library

1. Clone git repository:
```git clone https://github.com/augkik/contacts-2.git```
2. Launch Web service:
```docker-compose up```

Instructions:

GET 

List of all contacts:
```/contacts```

Contact with particular id:
```/contacts/<id>```

List of particular contact books:
```/contacts/<id>/books```

PUT

Update particular contact: ```/contacts/<id>```

Update particular contact book: ```/contacts/<id>/books/<isbn>```

DELETE

Remove particular contact: ```/contacts/<id>```

Remove particular contact book: ```/contacts/<id>/books/<isbn>```

POST

Add new contact: ```/contacts```

Add new book: ```/contacts/<id>/books```
