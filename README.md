This repository contains a docker image.

It is stored using Git LFS. [Click here](https://github.com/anonymous-author-world/castt/blob/master/docker-castt.tar.gz) and then click the Download button to get the full file.

Then run:

    docker load < docker-castt.tar.gz

This will create a local image tagged `fc-castt`.

Run it with:

    docker run -it fc-castt
