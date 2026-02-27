FROM eclipse-temurin:17-jre
RUN mkdir /opt/app
RUN mkdir /files
COPY target/shopizer.jar /opt/app
COPY --chown=root:root ./files /files
CMD ["java", "-jar", "/opt/app/shopizer.jar"]