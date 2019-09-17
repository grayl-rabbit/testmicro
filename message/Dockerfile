FROM java:8-jre

ADD ./target/message.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/message.jar"]

EXPOSE 5000