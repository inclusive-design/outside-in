outside-in
==========

The Outside-IN website


Build Docker image
==================

You can serve the website from a [Docker](https://docs.docker.com/get-docker) container.

Once you have Docker installed, run the following commands to build a Docker image and start a container:

* Build the image: `docker build -t outsidein .`
* Run the container: `docker run --name outsidein -p 8000:80 outsidein`

The website will be available at [http://localhost:8000](http://localhost:8000)

If you make changes to the website, repeat the steps to build the image and start a new container.
