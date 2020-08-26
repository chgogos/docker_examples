FROM ubuntu:latest

RUN apt-get -y update && apt-get install -y

RUN apt-get install build-essential git cmake autoconf libtool pkg-config -y

COPY . /usr/src/cpp_test

WORKDIR /usr/src/cpp_test

RUN clang++ -o Test main.cpp

CMD ["./Test"]