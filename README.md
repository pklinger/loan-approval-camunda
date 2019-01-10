## 1. Install maven

Make sure maven is installed
https://maven.apache.org/install.html

check if maven is installed: `mvn -version`

## 2. build project from main directory

mvn clean
mvn install

## 3.  copy built files from /target folder

a `/target` folder should appear on success. Copy the `.war` file from the target folder into your server's `webapps` folder, which should be similar to `camunda-bpm-tomcat-7.9.0\server\apache-tomcat-9.0.5\webapps\`