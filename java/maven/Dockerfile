FROM maven:latest

COPY . .

RUN mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -Dinte
RUN cd my-app

RUN mvn package

CMD ["java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App"]

# CMD ["mvn"]
