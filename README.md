# learn-jenkins
sfsfsfsf
mvn archetype:generate -DgroupId=com.MSRIT.app -DartifactId=Abhishek -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false

cd Abhishek
mvn package
java -cp target/Abhishek-1.0-SNAPSHOT.jar com.MSRIT.app.App
<role rolename="manager-script"/>
<user username="deployer" password="deployer" rolename="manager-script"/>
