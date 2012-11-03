##Tornado REST API
Tornado is an non-blocking, scalable web server. It can handle thousands of simultaneous standing connections, which means it is ideal for real-time web services

####Install:
+ http://jpython.blogspot.com/search/label/Tornado

###API call

####GET
+ http://127.0.0.1:8080/all_book/
+ http://127.0.0.1:8080/all_category/
+ http://127.0.0.1:8080/all/

####POST
+ add new book:
  - url : http://127.0.0.1:8080/all_book/
  - param : name, title, author
+ add new category:
  - url : http://127.0.0.1:8080/category/
  - param : name
