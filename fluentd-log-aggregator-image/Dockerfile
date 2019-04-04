# Base image from Fluentd
FROM fluent/fluentd

# Install plugin to forward logs from fluentd to elasticsearch
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri"]

# fluentd-elasticsearch configuration
COPY conf/fluent.conf /fluentd/etc/fluent.conf
