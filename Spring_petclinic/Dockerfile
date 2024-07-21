FROM amazoncorretto:17
LABEL author="Shahinur Islam Ahmed"
LABEL application="spring-petclinic"
RUN mkdir /app
COPY ./spring-petclinic-3.2.0-SNAPSHOT.jar /app
WORKDIR /app
EXPOSE 8080
CMD [ "java", "-jar","spring-petclinic-3.2.0-SNAPSHOT.jar" ]