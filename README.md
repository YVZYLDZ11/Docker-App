# Docker-App

Getting Started

The command you just ran

Congratulations! You have started the container for this tutorial! Let's Õrst explain the
command that you just ran. In case you forgot, here's the command:

> docker run -d -p 80:80 docker/getting-started

You'll notice a few Öags being used. Here's some more info on them:

> -d - run the container in detached mode (in the background)

> -p 80:80 - map port 80 of the host to port 80 in the container

> docker/getting-started - the image to use

Pro tip

You can combine single character Öags to shorten the full command. As an example, the command above
could be written as:

> docker run -dp 80:80 docker/getting-started


The Docker Dashboard

Before going any further, we want to highlight the Docker Dashboard, which gives you a
quick view of the containers running on your machine. 

It provides you access to container logs, lets you get a shell inside the container, and allows you to easily manage container
lifecycle (stop, remove, etc.)

To access the dashboard, follow the instructions in the Docker Desktop manual. If you open
the dashboard now, you will see this tutorial running! The container name ( jolly_bouman
below) is a randomly created name. So, you'll most likely have a diáerent name.


What is a container?

















