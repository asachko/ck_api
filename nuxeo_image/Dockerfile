FROM nuxeo:latest
COPY nuxeo_image/nuxeo.conf /docker-entrypoint-initnuxeo.d/nuxeo.conf
COPY nuxeo_image/amazon-s3-online-storage-1.9.6.zip /tmp/amazon-s3-online-storage-1.9.6.zip

#RUN ./bin/nuxeoctl mp-install /tmp/amazon-s3-online-storage-1.9.6.zip