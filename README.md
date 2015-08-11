# Docker-BDD

Hook BDD with Cucumber and friends in the Docker.

This docker image will setup following technology stack.

* Ubuntu with Ruby

* Ruby

* Rubygem

* PhantomJS

* Cucumber Capybara Poltergeist framework with BDDfire  


# How to use

Pull the docker image from DockerHub

            $ docker pull shashikant86/docker-bdd

Now wait for all provisioning done for you.

Once image is succesfully downloaded.

              $ docker run -t -i docker-bdd /bin/bash

Now you are inside the docker container and in '/opt/bdd/cucumber' directory.

Now you can run all BDDfire[https://github.com/Shashikant86/bddfire] rake tasks. Now we will use Poltergeist

               $ bundle exec rake poltergeist
