#
#A great intro/refresher - https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html


mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false


cd my-app

mvn package 

java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App

