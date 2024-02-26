<h1 align="center" id="title">Simple CRUD Movie API</h1>

<p id="description">This repository implements a basic CRUD (Create Read Update Delete) API for managing movie entries. It serves as a learning project for building RESTful APIs in Go using the net/http package.</p>

  
  
<h2>🧐 Features</h2>

*   Create: Adds new movie entries to a mock in-memory data store.
*   Read: Retrieves all movie entries or a specific entry by ID.
*   Update: Modifies existing movie entries by ID.
*   Delete: Removes movie entries by ID.

<h2>🛠️ Installation Steps:</h2>

<p>1. Clone the repository:</p>

```
git clone https://github.com/RyuuOsamu/Simple-CRUD-Movie-API.git
```

<p>2. Navigate to the project directory:</p>

```
cd Simple-CRUD-Movie-API
```

<p>3. Run the server:</p>

```
go run main.go
```

<p>4. Test in POSTMAN</p>

<h2> Methods:</h2>

| EndPoint      | Method        | Description                                                                             |
| ------------- |:-------------:|:----------------------------------------------------------------------------------------|
| `/movies`     | `GET`        | Retrieves all movies.                                                                    |
| `/movies/id`	| `GET`	       | Retrieves a specific movie by ID.                                                        |
| `/movies`	    | `POST`	     | Creates a new movie. Body: JSON object with movie details (title, year, director, etc.). |
| `/movies/id`	| `PUT`	       | Updates an existing movie by ID. Body: JSON object with updated movie details.           |
| `/movies/id`	| `DELETE`	   | Deletes a movie by ID.                                                                   |
