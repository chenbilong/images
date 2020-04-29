FROM quay.io/fluentd_elasticsearch/fluentd:v3.0.1
MAINTAINER chenbilong <chenbilong@outlook.com>
RUN fluent-gem install fluent-plugin-forest &&\
    fluent-gem install fluent-plugin-record-reformer &&\
    fluent-gem install fluent-plugin-kafka &&\
    fluent-gem install fluent-plugin-record-reformer &&\
    fluent-gem install fluent-plugin-remote_syslog_tls &&\
    fluent-gem install fluent-plugin-rewrite-tag-filter &&\
    fluent-gem install fluent-plugin-splunk-enterprise
