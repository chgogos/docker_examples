# Docker example 2

Container used C++ single file code compiled with clang, container used ubuntu:latest

* Build docker container

    $ docker build . -t cpp_test:1

* Run

    $ docker run --rm -it cpp_test:1
