FROM docker.elastic.co/elasticsearch/elasticsearch:7.17.19
LABEL maintainer Daisuke Takahashi <daisuke@extendwings.com>

RUN bin/elasticsearch-plugin install --batch analysis-kuromoji
RUN bin/elasticsearch-plugin install --batch analysis-icu
