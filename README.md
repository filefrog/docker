filefrog/docker
===============

Run Docker, in a Docker Container!

    $ docker run --rm \
        -v /var/run/docker.sock:/var/run/docker.sock \
        filefrog/docker \
        docker ps

