STOREFRONT--Django project


**A full Backend web application using Django framework and other functionalities for a storefront**
**The project is divided into three sections**
**seeds.sql is my dataset for the products in the store**


**SECTION 1:********************
1) Setting up the development environment
-installing python 
-installing pipenv 
-creating a storefront folder on desktop installing django using pipenv
-adding interpreter path in VScode

2) Creating the app
-creating playground folder
-mapping urls to views

3) Using Templates
-adding HTML template

4)Debugging Django application in VScode
-using Django debug toolbar

5) Creating Models
-creating store folder, tags folder, likes folder
-adding choice fields
-defining one-to-one, one-to-many and many-to-many relationships
-resolving cicular and generic relationships

6) Setting up Database
-i will use PostgreSQL 
-creating migrations
-customizing database migrations

7) Django ORM 
-querying data, manipulating data, filtering data, sorting data, grouping data
-creating objects, updating objects, deleting objects
-transactions

8) Django Admin
-customizing the admin interface
-adding computed columns
-loading related objects
-adding search and filter
-implementing custom actions
-adding data validation


**SECTION 2:********************
1)RESTful APIs
-installing Django REST framework
-creating API views
-creating serializers
-serializing and deserializing models

2)Advanced API
-class-based views
-generic views
-viewsets
-routers
-searching, filtering and pagination

3)Building API 
-create a serializer
-create a view
-register a route

4) Building a shopping cart API
-create a cart
-add items to a cart
-update the quantity of items
-remove items from a cart
-get a cart with its items
-delete a cart

5)Securing APIs
-token-based authentication 
-adding authentication endpoints
-registering, logging in , etc
-applying permissions

6)Building the Orders API
-Designing the orders API------ orders endpoint

7) Signals 
-creating custom signals

**SECTION 3:********************
1)Uploading files
-managing media files
-adding images to products
-building API to upload images
-returning images from the API
-validating uploading files
-setting up client apa
-enabling CORS--- reaches our code server
-managing images in the admin

2) Sending Emails
-setting up fake SMTP server from Docker-------smtp4dev @GitHup
-configuring the email backend
-sending emails
-attaching files
-sending templated emails

3)Running Background Tasks
-by using celery
-message broker using redis
-creating and excuting tasks
-scheduling periodic tasks
-monitoring celery tasks

4)Automated testing
-using pytest as my test framework------pytest-django------*pytest plugin for django
-running tests--------pytest.ini
-skipping tests
-running and debugging tests in VScode
-authenticating the users
-creating model instance----------using----model-bakery

5) Performance Testing
-by using Locust--------its realy simple and have a good UIN
-creating and running test scripts
-running a performance test on the locust site
-optimizing tests
-profiling with silk--------for the issues in query or in database
-verifying optimizations
-stress testing-------special type of performance test we use it to find our upper limits

6)Cashing
-cashe backends---------Redis---------a cashe server that is very good for production
-simulating a slow API
-getting a baseline performance benchmark
-installing redis
-configuring cashe
-using the low-level cashe API
-viewing cashe as a decrator
-verifying optimization using locust
-managing redis cashe content

7)Preparing For Production
-adding home page
-managing static files
-collecting static assets
-saving static assets
-configuring logging--------using logging for diagnosing the proplems
-managing development and production settings
-serving the application with witress 

8)Deployment
-my hosting option------platform-as-a-service-----------*i will us heroku-------------very simple, well decumented, and a beutiful platform
-adding project to Git
-creating a heroku app
-setting environment variables for heroku
-creating procfile for heroku
-provisioning a postgresql database, redis instance, SMTP server for heroku
-Deploying the application for heroku
-populating the database for heroku
-Deckorizing App--------------docker-compose------------to run all the services at once
