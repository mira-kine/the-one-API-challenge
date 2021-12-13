# Online data bases

## HTTP API SPA

### Lecture notes

- HTTP is a protocol used to request hypertext files
- React router: every react router application needs a router
- Route matching components: looks at URL in browser and matches it to routes defined in app
  - put longer paths before shorter paths, or use exact prop
  - react router searches through the <Route> elements within a <Switch> and when it finds a match, it renders that Route and ignores the others - for example <Route path="/contact/:id" component={Contact} /> means that we are using a component we created (contact) through the URL path /contact/:id where :id is a variable that can hold the specific information we want to access, all simplified within /contact/:id - this is helpful so you don't have hardcode multiple URL's like /contact/1, /contact/2
- Navigation (Route Changers) -> allows us to add links. If you use regular links it would just refresh the page, as though it is just an HTML element rather than changing the URL and re-rendering for us.

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
