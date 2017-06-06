FROM ubuntu:16.04
RUN apt-get -y update &&\
	apt-get install -y software-properties-common &&\
	add-apt-repository ppa:fkrull/deadsnakes &&\
	apt-get -y update &&\
	apt-get install -y python2.4 &&\
	apt-get remove --auto-remove -y software-properties-common 
