FROM java

COPY /opt/bitnami/apps/jenkins/jenkins_home/workspace/maven-test/spring-boot-examples/spring-boot-2-rest-service-basic/target/

WORKDIR /opt/bitnami/apps/jenkins/jenkins_home/workspace/maven-test/spring-boot-examples/spring-boot-2-rest-service-basic/target/

CMD ["java","-jar","/opt/bitnami/apps/jenkins/jenkins_home/workspace/maven-test/spring-boot-examples/spring-boot-2-rest-service-basic/target/spring-boot-2-rest-service-basic-0.0.1-SNAPSHOT.jar"]
