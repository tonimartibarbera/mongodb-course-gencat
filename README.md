### Mongosh Path
### C:\Users\jordi\Downloads\mongosh-1.7.1-win32-x64\bin
C:\Users\tonim\Documents\MongoSh\bin
### Mongosh Executes an external javascript file
mongosh "127.0.0.1/school" "C:\Users\tonim\Documents\MongoSh\scripts\GetStudents.js"
mongosh 127.0.0.1/school C:\Users\tonim\Documents\MongoSh\scripts\CreateSchoolSchema.js
### mongosh "mongodb+srv://cluster0.dsb8fht.mongodb.net/school" --apiVersion 1 --username jordi
### mongosh "mongodb+srv://cluster0.dsb8fht.mongodb.net/school" --apiVersion 1 --username jordi C:\Users\jordi\Downloads\mongosh-1.7.1-win32-x64\bin\scripts\GetStudents.js
mongosh "mongodb+srv://cluster0.uflb5z7.mongodb.net/School" --apiVersion 1 --username toni C:\Users\tonim\Documents\MongoSh\scripts\GetStudents.js
### execute Postman files via Newman
newman run NttData-Student-Gencat.postman_collection.json -e NttData-Student-PRO.postman_environment.json
### Execute CrudStudentsExercice.js to Atlas MongoDB Database
### mongosh "mongodb+srv://cluster0.dsb8fht.mongodb.net/school" --apiVersion 1 --username jordi C:\Users\jordi\Downloads\mongosh-1.7.1-win32-x64\bin\scripts\CrudStudentsExercice.js
mongosh "mongodb+srv://cluster0.uflb5z7.mongodb.net/School" --apiVersion 1 --username toni C:\Users\tonim\Documents\MongoSh\scripts\CrudStudentsExercise.js
### execute Postman files via Newman
newman run MongoDB-Data-API.postman_collection.json -e Data-API.postman_environment.json -r htmlextra