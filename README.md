single endpoint :  http://localhost:9002/rest/books
querying for a specific book whose id is 1001 and we want only the title in its response. Along with it, we are querying for allBooks and expecting that response will contain isn, title, author, publisher and publishedDate.
{
 book(id:"1001"){
 title
 }

 allBooks{
 isn
 title
 author
 publisher
 publishedDate
 }
}
you can query for book title and author or specific information.You are telling what you will need.