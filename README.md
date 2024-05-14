# Go Bookstore

This is a Go project for book management, similar to a bookstore, allowing you to manage a library of books.

## Requirements

- Go 1.21.6 or higher

## Installation

1. Clone the repository:

```bash
git clone https://github.com/jesbalchiero/bookstore-api.git
```

2. Navigate to the project directory:

```bash
cd bookstore-api
```

3. Run the application:

``` go
go run main.go
```

## Usage

Access the application at http://localhost:9010 to begin managing your bookstore.

## Features

Add books to the library

Update books to the library

Remove books from the library

List all books

Search for books by id

## Project Structure

- `/cmd/main/main.go`: Entry point of the application.
  
- `/pkg/config/app.go`: Database connection.
  
- `/pkg/controller/book-controller.go`: HTTP handlers to handle book-related requests.
  
- `/pkg/models/book.go`: Definition of the Book type and related functions.
  
- `/pkg/routes/bookstore-routes.go`: HTTP routes configuration.
  
- `/pkg/utils/utils.go`: Utility functions and helpers.

## Contributing

If you want to contribute to this project, feel free to open an issue or send a pull request.
