# udemy-kurs-postman

To start json-server, run:
```
json-server --watch db.json
```

To start Newman (Postman CLI), run e.g.:
```
newman run ./Generator\ recenzji\ książek.postman_collection.json

newman run ./Generator\ recenzji\ książek.postman_collection.json -e Dev.postman_environment.json 

newman run ./Generator\ recenzji\ książek.postman_collection.json -e Dev.postman_environment.json -d Books.csv
```