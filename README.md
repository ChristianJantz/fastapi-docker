# fastapi-docker
to start the image build 

    docker build -f fastapi.Dockerfile -t fastapi:0.1

# Run the image
to run the Docker image 

    docker run -p 3000:5000 fastapi:0.1

# Run the docker-compose 

# .Env FILE
to run thwe docker-compose you can use this example Enviroment File

    DB_USER=name-of-the-db-user-for-access-to-the-db
    DB_PASSWORD=password-of-the-db
    DB_NAME=invoice-db
    PGADMIN_EMAIL=admin@admin.com
    PGADMIN_PASSWORD=admin-stress-test

