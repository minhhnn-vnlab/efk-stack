FROM elasticsearch:8.10.2
RUN echo "xpack.security.enabled: false" >> /usr/share/elasticsearch/config/elasticsearch.yml
EXPOSE 9200
CMD ["elasticsearch"]