#FROM registry.access.redhat.com/ubi8/ubi-minimal
# mvn io.quarkus:quarkus-maven-plugin:1.9.2.Final:create     -DprojectGroupId=org.acme -DprojectArtifactId=getting-started -DclassName="org.acme.getting.started.GreetingResource" -Dpath="/hello"

# Red Hat image with JAVA 
#FROM registry.redhat.io/redhat-openjdk-18/openjdk18-openshift
 
# copy the packaged jar file into our docker image
#COPY target/getting-started-1.0-SNAPSHOT.jar /getting-started.jar
 
# set the startup command to execute the jar
#CMD ["java", "-jar", "/getting-started.jar"]

FROM registry.access.redhat.com/ubi8/openjdk-11:1.3
COPY target/*-runner.jar /deployments/app.jar
