FROM dockerfile/java:oracle-java8

ADD Demo_abhi.jar /opt/Demo_abhi/
EXPOSE 8080
WORKDIR /opt/Demo_abhi/
CMD ["java", "-Xms512m", "-Xmx1g", "-jar", "Demo_abhi.jar"]