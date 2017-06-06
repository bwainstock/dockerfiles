FROM centos:7
ENV PYVER 2.4.6
RUN yum groupinstall -y 'Development Tools'
RUN curl -O https://www.python.org/ftp/python/$PYVER/Python-$PYVER.tgz &&\
	tar zxf Python-$PYVER.tgz &&\
	cd Python-$PYVER &&\
	./configure &&\
	make &&\
	make install
RUN yum groupremove -y 'Development Tools'
