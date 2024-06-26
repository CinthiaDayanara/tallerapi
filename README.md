workshop members: Pablo Sanchez Dayanara Churaco

GET http://localhost:3000/books HTTP/1.1

###
GET http://localhost:3000/books/1 HTTP/1.1

###
POST http://localhost:3000/books HTTP/1.1
Content-Type: application/json

{
  "title": "Una breve historia del tiempo",
  "author": "Stephen Hawking",
  "year": 1988
}

###
PUT http://localhost:3000/books/3 HTTP/1.1
Content-Type: application/json

{
  "year": 1989
}

###
DELETE http://localhost:3000/books/3 HTTP/1.1
