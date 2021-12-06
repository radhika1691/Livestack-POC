FROM maven:ibmjava-alpine
WORKDIR /app/cloudconfigserver
COPY . /app
RUN mvn install
CMD ["mvn", "spring-boot:run"]
