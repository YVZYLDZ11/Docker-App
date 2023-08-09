# Docker-App

Getting Started

The command you just ran

Congratulations! You have started the container for this tutorial! Let's first explain the
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

Now that you've successfully run a container, let's ask ourselves what is a container? Simply
put, a container is another process on your machine that has been isolated from all other
processes on the host machine. That isolation leverages kernel namespaces and groups,
features that have been in Linux for a long time. Docker has worked to make these
capabilities approachable and easy to use.

What is a container image?

When running a container, it uses an isolated filesystem. This custom system is provided
by a container image.

Since the image contains the container's system, it must include
everything needed to run the application - all dependencies, conÕguration, scripts, binaries,
etc. The image also contains other conÕguration for the container, such as environment
variables, a default command to run, and other metadata.

We'll dive deeper into images later on, covering topics such as layering, best practices, and
more.


Info









