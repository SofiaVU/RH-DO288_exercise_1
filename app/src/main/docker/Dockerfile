FROM registry.access.redhat.com/ubi8/ubi-minimal
RUN mvn io.quarkus:quarkus-maven-plugin:1.9.2.Final:create     -DprojectGroupId=org.acme -DprojectArtifactId=getting-started -DclassName="org.acme.getting.started.GreetingResource" -Dpath="/hello"

