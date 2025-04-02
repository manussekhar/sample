Develop a REST API to manage users with basic CRUD operations.
Requirements:

    User Entity:

        id (Long, auto-generated)

        name (String, required, max 50 chars)

        email (String, required, unique)
        
        age (Integer, optional)

    API Endpoints:

        Create a user → POST /users

        Get all users → GET /users

        Get a user by ID → GET /users/{id}

        Delete a user → DELETE /users/{id}

Use a hashmap to store the users in memory.