FROM tomcat:8.0
WORKDIR /var/lib/jenkins/workspace/maven_project_first/java-tomcat-sample/target/
COPY . /usr/local/tomcat/webapps/
EXPOSE 8092
CMD ["catalina.sh", "run"]
