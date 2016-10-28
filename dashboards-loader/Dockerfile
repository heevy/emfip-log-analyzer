FROM ubuntu:16.04
RUN mkdir /dashboards
RUN apt-get update && apt-get install -yqq curl netcat vim-common
ADD load-dashboards.sh /
RUN chmod +x /load-dashboards.sh
CMD /load-dashboards.sh

