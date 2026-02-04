# Go Movies CRUD 🎬

<div align="center">
  
![Go](https://img.shields.io/badge/Go-1.25+-00ADD8?style=flat\&logo=go\&logoColor=white)
![REST API](https://img.shields.io/badge/REST-API-success?style=flat)
![Postman Tested](https://img.shields.io/badge/Tested%20With-Postman-orange?style=flat\&logo=postman)
![JSON](https://img.shields.io/badge/Data-JSON-blue?style=flat)
![MIT License](https://img.shields.io/badge/License-MIT-green?style=flat)

</div>

A backend REST API built using **Golang** that implements full **CRUD (Create, Read, Update, Delete)** operations for managing movie data. The API is tested using **Postman** to validate request handling, responses, and data flow.

This project focuses on strengthening **core backend fundamentals**, REST API design, and practical API testing.

---

## 🚀 Project Overview

**Go Movies CRUD** is a simple movie management backend service where clients can:

* Add new movies
* Retrieve all movies or a single movie
* Update existing movie details
* Delete movies

All API endpoints follow RESTful principles and return structured responses.

---

## 🛠️ Tech Stack

* **Language:** Golang
* **Backend:** Go standard library (`net/http`)
* **API Style:** REST
* **Testing Tool:** Postman
* **Data Format:** JSON

---

## ✨ Features

* RESTful API design
* Full CRUD operations
* JSON request and response handling
* HTTP method validation (GET, POST, PUT, DELETE)
* Structured routing and handlers
* Tested end-to-end using Postman

---

## 📂 Project Structure

```
Go-Movies-CRUD/
│── main.go        # API server, routes, and handlers
│── go.mod         # Go module file
```

---

## 🔗 API Endpoints

### ➕ Create Movie

```
POST /movies
```

### 📥 Get All Movies

```
GET /movies
```

### 📄 Get Movie by ID

```
GET /movies/{id}
```

### ✏️ Update Movie

```
PUT /movies/{id}
```

### ❌ Delete Movie

```
DELETE /movies/{id}
```

---

## 🧪 API Testing with Postman

All endpoints are tested using **Postman** to verify:

* Correct HTTP methods
* Proper request payload handling
* Accurate responses
* Status codes

### 📸 Postman Screenshots

* POST request (Create movie)
* GET request (Fetch movies)
* PUT request (Update movie)
* DELETE request (Delete movie)

**Create Movie (POST)**
![Create Movie](screenshots/create-movie.png)

**Result of Create Movie (GET)**
![Result of Create Movie](screenshots/create-movie-result.png)

**Get all Movies (GET)**
![Get all Movies](screenshots/get-movies.png)

**Get a Movie by ID (GET)**
![Get a Movie by ID](screenshots/get-movie-by-id.png)

**Update Movie (PUT)**
![Update Movie](screenshots/update-movie.png)

**Result of Update Movie (GET)**
![Result of Update Movie](screenshots/update-movie-result.png)

**Delete Movie (DELETE)**
![Delete Movie](screenshots/delete-movie.png)


---

## ▶️ How to Run the Project

### Prerequisites

* Go installed on your system
* Postman (for testing)

### Steps

```bash
go build
```

```bash
go run main.go
```

The server will start on the configured port:

```
http://localhost:8000
```

---

## 🧠 Concepts Learned

* REST API design principles
* HTTP methods and routing
* JSON encoding and decoding in Go
* CRUD operations implementation
* API testing using Postman
* Backend project structuring

---

## ⚠️ Limitations

* No database integration (in-memory data handling)
* No authentication or authorization
* No pagination or filtering

These features can be added in future enhancements.

---

## 🔮 Future Improvements

* Integrate a database (MongoDB / PostgreSQL)
* Add authentication (JWT)
* Input validation and error handling
* Pagination and filtering
* Deployment and environment configuration

---

## 📌 Resume Description

> Built a RESTful CRUD API using Golang to manage movie data, implementing create, read, update, and delete operations, and tested all endpoints using Postman.

---

## 📬 Feedback

Suggestions and feedback are welcome. Feel free to raise an issue or connect with me.

---

⭐ If you find this project useful, consider starring the repository!
