# dhee-widget-examples
Example HTML files showing default and customized usage of Dhee.AI's web widget.

# Install JAVA
Make sure JAVA 8 or above version is installed in the system. 
https://docs.oracle.com/en/java/javase/15/install/overview-jdk-installation.html#GUID-8677A77F-231A-40F7-98B9-1FD0B48C346A

Open JDK For Ubuntu
$ sudo apt update
$ sudo apt install default-jdk

# Install MAVEN
Make sure MAVEN is installed in the system.
https://maven.apache.org/

Maven For Ubuntu
$ sudo apt-get install maven

# Build
Please clone the project and navigate to the project.
$ mvn clean package -DskipTests=true

# Run
$ java -jar target/dhee-widget-examples-0.0.1-SNAPSHOT.jar
