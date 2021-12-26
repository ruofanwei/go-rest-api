### go-rest-api

> A simple REST API

### Features
- `GET /movies` returns list of movies
- `GET /movies/{id}` returns details of specific movie as JSON
- `POST /movies` accepts a new movie to be added
- `PUT /movies/{id}` update details of specific movie
- `DELETE /movies/{id}` delete details of specific movie

### Data Types
A movie object look like this:

```json
{
  "id": "1",
  "isbn": "438227",
  "title": "Emily in Paris",
  "director": {
    "firstname": "Michael",
    "lastname": "Amodio"
  }
}
```
