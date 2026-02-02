# Simple Web Server in Go

A beginner-friendly backend project built using **Golang's standard library** to understand how web servers work at a low level. This project demonstrates how HTTP requests are handled, how routes are defined, and how HTML pages and form data are served without using any external frameworks.

---

## 🚀 Project Overview

This project implements a basic HTTP server using Go’s `net/http` package. It serves static HTML pages, handles routing, and processes form submissions from the client.

The main goal of this project is to build a strong foundation in backend development by understanding the **request–response lifecycle** and **server-side logic**.

---

## 🛠️ Tech Stack

* **Language:** Golang
* **Backend:** Go standard library (`net/http`)
* **Frontend:** HTML
* **Architecture:** Client–Server (HTTP based)

---

## ✨ Features

* Starts an HTTP server on a local port
* Handles multiple routes using handler functions
* Serves static HTML files
* Processes form data submitted via POST requests
* Demonstrates GET vs POST request handling

---

## 📂 Project Structure

```
project/
│── main.go # Server logic and route handlers
│── static/ # Static files served by the server
│ │── index.html # Home page
│ │── form.html # HTML form page
```

---

## ⚙️ How It Works

1. The Go server listens on a specific port using `http.ListenAndServe()`
2. Incoming HTTP requests are mapped to handler functions
3. Handler functions process the request and send responses back to the client
4. HTML files are served to the browser
5. Form data is read and processed on the backend

---

## ▶️ How to Run the Project

### Prerequisites

* Go installed on your system

### Steps

```bash
go mod init
```
```bash
go build
```
```bash
go run main.go
```

Then open your browser and visit:

```
http://localhost:8080
```

---

## 🧠 Concepts Learned

* HTTP request–response lifecycle
* Routing in Go using `net/http`
* Handler functions and server-side logic
* Serving static files
* Handling form data in backend
* Basic backend project structuring

---

## ⚠️ Limitations

This project is intentionally kept simple:

* No database integration
* No authentication or authorization
* No middleware or logging
* No concurrency handling

These features can be added in future iterations as part of advanced backend projects.

---

## 🔮 Future Improvements

* Add REST APIs returning JSON
* Integrate a database (MySQL/PostgreSQL)
* Add input validation and error handling
* Use a router framework (Fiber / Gorilla Mux)
* Implement authentication (JWT)

---

## 📌 Why This Project Matters

This project focuses on **core backend fundamentals** instead of frameworks. It proves the ability to:

* Understand how servers work internally
* Build backend logic from scratch
* Explain backend concepts clearly in interviews

---

## 📄 Resume Description

> Built a simple web server using Golang’s `net/http` package to handle HTTP requests, serve HTML pages, and process form data, demonstrating core backend fundamentals.

---

## 📬 Contact

If you have suggestions or feedback, feel free to reach out or raise an issue.

---

⭐ If you found this project useful, consider starring the repository!
