
## Running the server

The easiest way to build and run the server to run in a single command

```
go build && ./restapi
```

## Two step way to build and then run the server

### Step 1. Build the code


```
go build
```

### Step 2. run the server

```
./restapi
```


## Build main.go

```
go run main.go
```


## Command to install mux

Run this command on your terminal
```
go get -u https://github.com/gorilla/mux
```


## API Url to view all the books

```
http://localhost:8000/api/books
```


## API Url to view a book by id

```
http://localhost:8000/api/book/2
```
