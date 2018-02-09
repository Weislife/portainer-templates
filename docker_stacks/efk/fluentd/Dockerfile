# docker build --rm -t fluentd-efk .
FROM fluent/fluentd
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri"]
RUN ["gem", "install", "fluent-plugin-rewrite-tag-filter"]
