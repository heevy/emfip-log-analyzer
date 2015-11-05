FROM elasticsearch:latest
COPY plugins/java-stacktrace-normalizer-2.0.0.zip /tmp/
RUN plugin install file:///tmp//java-stacktrace-normalizer-2.0.0.zip
#RUN plugin install license
#RUN plugin install marvel-agent
#ENTRYPOINT 
CMD ["elasticsearch","-Des.network.bind_host=0.0.0.0"]
