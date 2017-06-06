FROM bwainstock/python:2.7-centos
VOLUME /app
WORKDIR /app
RUN echo 'alias yum="yum --nogpg"' >> ~/.bashrc &&\
	/bin/bash -c "source ~/.bashrc"
CMD ["/bin/bash", "-c", "nosetests", "-v"]
