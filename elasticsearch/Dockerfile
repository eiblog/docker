FROM elasticsearch:2.4.3
LABEL maintainer="deepzz.qi@gmail.com"

ENV ES_JAVA_OPTS="-Xms512m -Xmx512m"
ADD config /usr/share/elasticsearch/config
ADD plugins /usr/share/elasticsearch/plugins
