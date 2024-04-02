FROM docker.elastic.co/elasticsearch/elasticsearch:8.13.0
LABEL maintainer Daisuke Takahashi <daisuke@extendwings.com>

RUN bin/elasticsearch-plugin install --batch analysis-kuromoji
RUN bin/elasticsearch-plugin install --batch analysis-icu
