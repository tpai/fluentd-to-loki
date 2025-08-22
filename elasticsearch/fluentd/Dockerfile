FROM fluent/fluentd:v1.19-2
USER root
# Elasticsearch plugin
RUN gem install elasticsearch -v "~> 8.0"
RUN gem install fluent-plugin-elasticsearch
USER fluent
