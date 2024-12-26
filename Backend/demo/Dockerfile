FROM eclipse-temurin
WORKDIR /app
 
COPY .mvn/ .mvn
COPY mvnw pom.xml ./
RUN ./mvnw dependency:go-offline
 
COPY src ./src
 
CMD ["java","-jar",,"MoviesSpring-0.0.1-SNAPSHOT.jar"]
