FROM anapsix/alpine-java
MAINTAINER bronius.janonis@gmail.com
ADD word-parser-eureka-service.jar /opt/word-parser-eureka-service.jar
ADD start.sh .
EXPOSE 8010
CMD ["bash", "start.sh"]
