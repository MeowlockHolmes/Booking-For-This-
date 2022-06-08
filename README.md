# bbm384-project-spring2020-honto


# API Documentation

**Url:** [https://bbm384-project.herokuapp.com](https://bbm384-project.herokuapp.com)

## Book API

**Get All Books:** [GET: /api/v1/books](https://bbm384-project.herokuapp.com/api/v1/books)

* Returns all the books recorded in the system

**Get A Book:** [GET: /api/v1/books/{bookID}](https://bbm384-project.herokuapp.com/api/v1/books/751d6e05-cdbc-4c6c-b194-99d744131e66)

* Returns the book with the given ID

**Update A Book:** [PUT: /api/v1/books/{bookID}]()

* Updates the properities of the book with the given ID according to the request body

**Delete A Book:** [DELETE: /api/v1/books/{bookID}]()

* Deletes the book with the given ID from the system

## Author API

**Get All Authors:** [GET: /api/v1/authors](https://bbm384-project.herokuapp.com/api/v1/authors)

* Returns all the authors recorded in the system

**Get An Author:** [GET: /api/v1/authors/{authorID}](https://bbm384-project.herokuapp.com/api/v1/authors/7f4341dc-6d1e-44fb-812d-175ded3382dd)

* Returns the author with the given ID

**Update An Author:** [PUT: /api/v1/authors/{authorID}]()

* Updates the properities of the author with the given ID according to the request body

**Delete An Author:** [DELETE: /api/v1/authors/{authorID}]()

* Deletes the author with the given ID from the system

## Publisher API

**Get All Publishers:** [GET: /api/v1/publishers](https://bbm384-project.herokuapp.com/api/v1/publishers)

* Returns all the publishers recorded in the system

**Get A Publisher:** [GET: /api/v1/publishers/{publisherID}](https://bbm384-project.herokuapp.com/api/v1/publishers/85102947-669a-4164-8f30-55212b541df6)

* Returns the publisher with the given ID

**Update A Publisher:** [PUT: /api/v1/publishers/{publisherID}]()

* Updates the properities of the publisher with the given ID according to the request body

**Delete A Publisher:** [DELETE: /api/v1/publishers/{publisherID}]()

* Deletes the publisher with the given ID from the system
