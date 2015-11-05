FROM ubuntu
VOLUME /input-dir
RUN apt-get update && apt-get install -yqq unzip
COPY discoverAndIndex.sh /bin/
CMD /bin/discoverAndIndex.sh
