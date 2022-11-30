# composetest

Here first of all a python app is created.

After that requirements.txt is created according to the dependencies which the app require to run.

Then a Dockerfile created to build an image for our application. From this Dockerfile we can create our own image for the containerization of our app.

At the end according to our Dockerfile a docker-compose.yaml file created in order to easily manage our containers and environment.

Docker compose allows us to manage more than container easily. But it is more suitable for test environment. For production Kubernetes is more suitable option.
