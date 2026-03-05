################################################
#             JAVA MICROSERVICE IMAGE          #
################################################
FROM registry.access.redhat.com/ubi9/openjdk-17-runtime:1.20

ENV JAVA_OPTIONS="-Dfile.encoding=UTF-8"
ENV AB_OFF=true

COPY ./target/firstapp-impl-0.0.1-SNAPSHOT.jar /deployments/
