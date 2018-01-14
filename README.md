If you want to run the python script in this repo do these things:

clone the repo

navigate to the top level dir - the one with the docker-compose.yml file in it

run this command: docker-compose build

then this command: docker-compose up -d

then this command: docker-compose exec ml /bin/bash

it will give you a prompt in the container

then run this command: python ml_entrance_questions.py -dataset music

that will run my tests for the music dataset - warning: it takes a long time - Enjoy (;
