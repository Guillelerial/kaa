# kaa
----------------------------------------------
MSIET-IARS: kaa &lt;-> node-red 

## Contribution guidelines
1. No direct pushing to ``master`` or ``develop`` branches within the repo.
2. Branch off of ``develop``, contribute feature, submit pull request within github back to the ``develop`` branch.

## How to run node-red

cd to repo
cd node-red
docker-compose up

Access through localhost:1880 on your browser of choice

### Fresh start of docker instances
1. Stop and delete all active dockers ``docker rm $(docker ps -a -q) -f``
2. Remove all images ``docker rmi $(docker images -a -q) -f``

