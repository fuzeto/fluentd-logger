# fluentd/Dockerfile
FROM fluent/fluentd:v1.10-1
USER root
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "4.0.2"]
RUN ["gem", "install", "fluent-plugin-s3", "--no-document", "--version", "1.1.0"]