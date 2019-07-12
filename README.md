# cd-demo

Continuous Deployment Demo

Just some static content served by nginx.

Build the image:

    $ docker build -t showaltb/cd-demo .

Run the image on port 8080:

    $ docker run --rm -p080:80 showaltb/cd-demo

Remove the image

    $ docker rmi showaltb/cd-demo
