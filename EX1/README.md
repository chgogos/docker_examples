# Docker example 1

C++ single file code compiled with g++, container used gcc:latest

* Build docker container

    $ docker build . -t cpp_test:1

* Run

    $ docker run --rm -it cpp_test:1
