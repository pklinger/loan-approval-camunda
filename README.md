## 1. Install maven

Make sure maven is installed
https://maven.apache.org/install.html

check if maven is installed: `mvn -version` on your command line

## 2. build project from main directory

type
`mvn clean`
then
`mvn install`
into your command line terminal

## 3.  copy built files from /target folder

a `/target` folder should appear on success respectively the project will be rebuilt. Copy the `.war` file from the target folder into your server's `webapps` folder, which should be similar to `camunda-bpm-tomcat-7.9.0\server\apache-tomcat-9.0.5\webapps\`
