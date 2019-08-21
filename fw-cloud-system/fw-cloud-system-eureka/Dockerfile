FROM java:8
MAINTAINER fw-cloud-framework <liuweijw.github@foxmail.com>

ADD ./target/fw-cloud-system-eureka.jar /app/

CMD ["java", "-Xmx200m", "-jar", "/app/fw-cloud-system-eureka.jar"]

EXPOSE 1001