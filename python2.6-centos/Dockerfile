FROM centos:6
ENV NOSE_VERSION nose-1.3.7
WORKDIR /nose
COPY $NOSE_VERSION.tar.gz /nose
RUN tar zxf $NOSE_VERSION.tar.gz &&\
	cd $NOSE_VERSION &&\
	python setup.py install &&\
	cd .. &&\
	rm -rf $NOSE_VERSION $NOSE_VERSION.tar.gz
CMD ["/bin/sh"]
