FROM bwainstock/python:2.7-centos
VOLUME /app
WORKDIR /app
RUN echo 'alias yum="yum --nogpg"' >> ~/.bashrc
CMD ["nosetests", "-v"]
