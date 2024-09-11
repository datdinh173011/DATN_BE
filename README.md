### For Developer

1. Build the Docker images:
    Run the following command in the directory containing your docker-compose.yml and Dockerfile:
    ```bash
    $ docker-compose build
    ```

2. Run the containers: Start the services using::

    ```bash
    $ docker-compose up -d
    ```

    Now the server is running on: http://localhost:8000/

3. Optional: Access the Django Container

    ```bash
    $ docker-compose exec web bash
    ```
