# Docker

Images Created:
1. Mongo Image
2. Node Image
3. React Image

Containers Created:
1. MongoDB Container
   - Image: Mongo Image
   - Purpose: To run the MongoDB database.
   - Configuration: Uses volumes to persist data.

2. Node.js Backend Container
   - Image: Node Image
   - Purpose: To run the Node.js backend application.
   - Configuration: Exposes port 8000:80 and connects to the MongoDB container.

3. React.js Frontend Container
   - Image: React Image
   - Purpose: To run the React.js frontend application.
   - Configuration: Exposes port 3000:3000.

Networking:
- Docker Network: Used to create a bridge network to allow communication between containers.

Orchestration with Docker Compose:
- docker-compose.yml: A YAML file that orchestrates the deployment and configuration of these containers and networks.
