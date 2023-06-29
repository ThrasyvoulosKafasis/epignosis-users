# Mock API Documentation

Feel free to preview the [mocked users REST API](https://my-json-server.typicode.com/ThrasyvoulosKafasis/epignosis-users). The specific API doesn't require any authorization, so you can easily perform and test the below CRUD actions. Keep in mind that you cannot mutate or edit anything from the "users" resource, so don't expect persistance on your changes. With this as a fact, we expect from your project to correctly perform all the appropriate requests (with the correct methods and data). Below you can read more details regarding the requests that you need to perform:

# Get all users

METHOD: GET

URL: https://my-json-server.typicode.com/ThrasyvoulosKafasis/epignosis-users/users

# Get single user

METHOD: GET

URL: https://my-json-server.typicode.com/ThrasyvoulosKafasis/epignosis-users/users/:id

example: https://my-json-server.typicode.com/ThrasyvoulosKafasis/epignosis-users/users/5c093af1c6ee9117a581c7d6

# Update user

METHOD: PUT

URL: https://my-json-server.typicode.com/ThrasyvoulosKafasis/epignosis-users/users/:id

example: https://my-json-server.typicode.com/ThrasyvoulosKafasis/epignosis-users/users/5c093af1c6ee9117a581c7d6

DATA: {
"name": "John Doe",
"company": "epignosis",
"email": "email@test.com"
}

Note: Put only the changed fields.
