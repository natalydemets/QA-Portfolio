This folder contains my Postman Practice collection for the Conduit API.

What is inside
Postman collection export (.postman_collection.json)
Optional environment export (.postman_environment.json), if present

How I built it
Requests are organized by folders (Articles, Profile, Comments, and others)
All requests are independent and create required test data in Pre-request scripts
Collection-level variables are used (url, passwordConduit)
Each request contains tests, and repeating logic is reused via helper functions

API under test
https://conduit.mate.academy/api/
