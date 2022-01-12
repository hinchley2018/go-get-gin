# go-get-gin
- a simple golang gin app to be deployed on gcp


## Getting started
- make sure golang installed locally `go version`
- make sure packages are up to date `go mod tidy`

## Running the app
- `go run main.go`
- use postman or browser `http://localhost:8080/garnishes`


## Deployment
- signup with gcp
- download gcloud cli tool and follow directions to connect to a project
- once your project is connected
- deploy the app `gccloud app deploy`