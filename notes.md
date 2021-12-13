# Online data bases

## HTTP API SPA

### Lecture notes

- HTTP is a protocol used to request hypertext files

### HTTP Verbs

- GET
- POST
- PATCH
- PUT
- DELETE

### HTTP Response Codes

- 200 - OK
- 404 - Not Found
- 301 - Redirect
- 500 - Server Error
- 418 - I'm a teapot (fun ways to remember http response codes at http.cat/#)

### The 7 RESTful routes

- index + /users + GET (lists all users)
- new + /users/new + GET
- Create + /users + POST (creates a new user)
- Show + /user/:id + GET (displays info for user with specific ID) => the colon (:) means that what comes afterwards will change, aka it is a variable
- Edit + /users/:id/edit + GET + Shows edit form for user with a specific ID
- Update + users/:id + PUT (updates user with specific ID)
- Destroy + users/:id + DELETE (deletes user)