# First Django Project GOAL TO MASTER PYTHON!!!!!

## PYTHON ROADMAP 
### Week 1: Python & API Fundamentals
Days 1-3: Python Fundamentals

* - [ ] Day 1: Environment Setup & Core Concepts

    * - [ ] Task: Set up a new project. Use python -m venv venv to create a virtual environment, activate it (source venv/bin/activate), and install a test package with pip install requests.

    * - [ ] Task: Review Python's core data types and control flow (if/elif/else, for loops).

    * - [ ] Task: Create a simple script with a function that takes arguments and returns a value.

* - [ ] Day 2: Pythonic Power Features

    * - [ ] Task: Practice creating lists and dictionaries using list and dict comprehensions.

    * - [ ] Task: Write a simple decorator that prints "Hello from the decorator!" before and after a function runs.

    * - [ ] Task: Create a generator function using the yield keyword that produces a sequence of numbers.

* - [ ] Day 3: Asynchronous Programming & Testing

    * - [ ] Task: Write a simple async function using asyncio that "sleeps" for a second and prints a message. Run it using asyncio.run().

    * - [ ] Task: Practice exception handling with try...except...finally blocks.

    * - [ ] Task: Set up pytest and write a few unit tests for the functions you created on Days 1 and 2.

Days 4-6: Web Framework & API

* - [ ] Day 4: Introduction to FastAPI

    * - [ ] Task: Install FastAPI and uvicorn.

    * - [ ] Task: Create a new FastAPI application.

    * - [ ] Task: Define a basic GET route that returns a JSON object.

    * - [ ] Task: Run the application and access the interactive API docs at http://127.0.0.1:8000/docs.

* - [ ] Day 5: Request Handling

    * - [ ] Task: Create a GET route that accepts a path parameter (e.g., /items/{item_id}).

    * - [ ] Task: Create a GET route that accepts a query parameter (e.g., /search?q=query).

    * - [ ] Task: Define a Pydantic BaseModel for an object and create a POST route that accepts this model in the request body.

* - [ ] Day 6: Building a Simple CRUD API

    * - [ ] Task: Create an in-memory list to store your data (don't worry about a real database yet).

    * - [ ] Task: Implement the "Create" (POST) and "Read" (GET) parts of a CRUD API for your in-memory list.

    * - [ ] Task: Implement the "Update" (PUT) and "Delete" (DELETE) parts of the API.

### Week 2: Database & Advanced Concepts
Days 7-9: Database Integration

* - [ ] Day 7: Introducing a Database with SQLAlchemy

    * - [ ] Task: Install SQLAlchemy and sqlite3.

    * - [ ] Task: Define a declarative base and create a simple User model with fields like id, name, and email.

    * - [ ] Task: Create a database file and use SQLAlchemy to create the table based on your model.

* - [ ] Day 8: Connecting the API

    * - [ ] Task: Connect your FastAPI application to the database.

    * - [ ] Task: Update your API's POST route to create a new record in the database instead of the in-memory list.

    * - [ ] Task: Update your API's GET route to read records directly from the database.

* - [ ] Day 9: Completing Database CRUD

    * - [ ] Task: Implement a PUT route to update an existing record in the database.

    * - [ ] Task: Implement a DELETE route to remove a record from the database.

Days 10-12: Advanced Database & API

* - [ ] Day 10: Advanced Database Management & SQL

    * - [ ] Task: Learn about database indexing and how to add an index to your User model to improve query performance.

    * - [ ] Task: Discuss query optimization techniques and use SQLAlchemy's explain() method to see how a query is executed.

    * - [ ] Task: Practice executing raw SQL queries directly through SQLAlchemy to see how it works under the hood.

* - [ ] Day 11: Authentication

    * - [ ] Task: Install python-jose and passlib.

    * - [ ] Task: Create a User model with a hashed password field.

    * - [ ] Task: Implement a registration endpoint that securely hashes and stores a new user's password.

    * - [ ] Task: Implement a login endpoint that verifies a password and generates a JSON Web Token (JWT).

* - [ ] Day 12: Authorization

    * - [ ] Task: Create a dependency in FastAPI that verifies a JWT and returns the current user.

    * - [ ] Task: Use this dependency to protect a specific route (e.g., /protected).

    * - [ ] Task: Implement a simple authorization check to ensure the logged-in user can only access their own data.

### Week 3: Scaling, Security, & Deployment
Days 13-15: Advanced Security & Performance

* - [ ] Day 13: Advanced Security

    * - [ ] Task: Implement a simple rate-limiting middleware for your API to protect against brute-force attacks.

    * - [ ] Task: Understand and discuss Cross-Site Scripting (XSS) prevention strategies and how FastAPI/Starlette helps.

    * - [ ] Task: Learn best practices for secure credential management and why you should never hardcode secrets.

* - [ ] Day 14: Caching & Scalability

    * - [ ] Task: Learn about different caching strategies (in-memory vs. external like Redis).

    * - [ ] Task: Use functools.lru_cache to cache the result of a CPU-intensive function to see the performance improvement.

    * - [ ] Task: Research the concept of load balancing and how it fits into a scalable architecture.

* - [ ] Day 15: Asynchronous Tasks & Message Queues

    * - [ ] Task: Create a route that performs a simulated long-running task using asyncio.sleep().

    * - [ ] Task: Research message queues (like RabbitMQ or Redis) and their use cases for decoupling long-running tasks from the main request/response cycle.

Days 16-18: Deployment & Final Review

* - [ ] Day 16: Containerization with Docker

    * - [ ] Task: Write a simple Dockerfile to containerize your FastAPI application.

    * - [ ] Task: Write a docker-compose.yml file that defines two services: your application and a PostgreSQL database.

    * - [ ] Task: Use docker-compose up to run your entire stack locally.

* - [ ] Day 17: Deployment to a Cloud Provider

    * - [ ] Task: Research the steps to deploy your Dockerized application to a cloud platform like Google Cloud, AWS, or Azure.

    * - [ ] Task: Learn about Continuous Integration/Continuous Deployment (CI/CD) pipelines.

* - [ ] Day 18: Final Review & Next Steps

    * - [ ] Task: Review the entire project, ensuring all components are working together.

    * - [ ] Task: Discuss next steps: adding more features, exploring more advanced testing methodologies, or building a new project from scratch.

Days 19-21: The Master's Touch

* - [ ] Day 19: Advanced Database Management (NoSQL)

    * - [ ] Task: Learn about NoSQL databases and their use cases.

    * - [ ] Task: Install motor (an async driver for MongoDB) and set up a connection to a MongoDB instance.

    * - [ ] Task: Create a new API route that uses a NoSQL database instead of or in addition to your SQL database.

* - [ ] Day 20: Advanced API Design

    * - [ ] Task: Implement API versioning (e.g., adding /v1/ to your URLs) to prepare for future changes.

    * - [ ] Task: Implement pagination on your GET endpoints to handle large datasets efficiently.

    * - [ ] Task: Use advanced Pydantic features like Field and conint for more robust validation.

* - [ ] Day 21: Capstone Project & Documentation

    * - [ ] Task: Choose a small, creative project idea that integrates all the concepts you've learned.

    * - [ ] Task: Implement the project, ensuring it uses both SQL and NoSQL databases, authentication, and a containerized setup.

    * - [ ] Task: Write clear and concise documentation for your final project, explaining the API, its dependencies, and how to deploy it.