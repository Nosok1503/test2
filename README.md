# test2
docker cp root/tomcat/spring-boot-prometheus-example /opt/apache-tomcat-8.5.57/webapps

cd /opt/apache-tomcat-8.5.57/webapps/spring-boot-prometheus-example

mvn clean package

mvn spring-boot:run


