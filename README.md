# README

Things you may want to cover:

* Ruby version
ruby 2.4.0p0

* System dependencies


* Database initialization
The database used is PostgresQL
Database Structure: 
One model is the Url and another is the Header (which contains a reference to the id # of the Url), Sample of the Database setup:

         URL 
   ID       URL(string)
    1       http://www.google.com 
    2       http://www.facebook.com
    
    
        Header
   ID       Tag(string)     Content(text)         url_id(reference)      
    1         "H3"            "Welcome to facebook"      2
    2         "H1"            "Login to facebook"        2
    3         "H2"            "Search with google"       1
* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
