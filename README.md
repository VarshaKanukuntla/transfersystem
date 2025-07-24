# transfersystem


#Install Vs code ,postgreSql Database, Postman
  write the code(as code is already in github sync the code)
  steps to execute the code 
     go mod init transfersystem
     go mod tidy 

     go get "github.com/gorilla/mux"

    go get "github.com/jmoiron/sqlx"
    go get 	_ "github.com/lib/pq"
    create table in POSTGRESQL database

$env:DATABASE_URL = "postgres://postgres:Saikumar%40123@localhost:5432/transferdb?sslmode=disable"

go run main.go
open postman application  and check the working as expected

  
