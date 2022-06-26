FROM openjdk:11-oracle

#To prevent ownership issues in creating journaling files in activemq dfault directories
USER root
EXPOSE 61616

ADD https://archive.apache.org/dist/activemq/5.16.0/apache-activemq-5.16.0-bin.tar.gz .

CMD ["apache-activemq-5.16.0/bin/activemq", "console"]







