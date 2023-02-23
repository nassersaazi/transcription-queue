## Node api for Bitcoin Transcripts

### Prerequisites

- Docker and docker-compose(preferrably latest stable versions)
- Ensure ports 8080,5433 and 5432 are open and accept connections (to access the backend api)
- Ensure port 3000 is open to accept connections (to access the frontend client)
    
### Steps to set up

- Clone the repository
- Inside the root directory ,run `docker-compose up -d`
- Access the api here: `http://localhost:8080`
- Access the frontend client here: `http://localhost:3000`


### Some endpoints to check out 

#### GET requests

-   `http://localhost:8080/api/transcripts`
-   `http://localhost:8080/api/users`

### TODOS:
- // Add swagger api documentation
- // Set up the application on AWS
- // Supply more meaningful data in the init.sql file

