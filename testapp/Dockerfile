FROM java:8
VOLUME /tmp
ADD testapp.jar testapp.jar
EXPOSE 8080
ENTRYPOINT ["java","-cp","/testapp.jar", "kixeye.testapp.Main"]
