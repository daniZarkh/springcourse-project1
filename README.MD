The project demonstrates basic usage of Spring, MVC structure, validator, SQL, HQL, Thymeleaf, HTML. The project represents itself as an accounting system in a library, where users of the library are registered and books are assigned to the users.

1. Artifact deployment using Tomcat v.9 should be set before running the server.
2. In browser, enter http://localhost:8080/people
3. There you can read information about users of books or enter new person data ("Добавить человека"). By clicking on person's name you can choose, whether to edit his data ("Редактировать") or to delete this person's entry completely ("удалить"). Also, by clicking on person's name you can you can find out which books does he currently posess.
4. In browser, enter http://localhost:8080/books
5. There you can read information about books (title, author, year of publishing) or enter new book data ("Добавить книгу"). By clicking on books's title you can choose, whether to edit its data ("Редактировать"), to delete this book's entry completely ("удалить"), or to assign the book to the one of users (on the book's page choose a name of a particular user and press "Назначить книгу").
6. When the book is returned to the library press "Освободить книгу".

Information about a current user of each book is updated simultaneously on all pages. 
