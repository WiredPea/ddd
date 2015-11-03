# ddd
Disposable Drupal using Docker.

# Quickstart.
    docker-machine create --driver virtualbox ddd
Copy and paste the output of
    docker-machine env ddd

    docker-compose up

You should now be able to connect to the ip of DOCKER\_HOST on port 8080
If that works, you dan download a Drupal installation in application.
