# dhee-widget-examples
Example HTML files showing default and customized usage of Dhee.AI's web widget.

# Install JAVA
Make sure JAVA 8 or above version is installed in the system.
<br/>
https://docs.oracle.com/en/java/javase/15/install/overview-jdk-installation.html#GUID-8677A77F-231A-40F7-98B9-1FD0B48C346A
<br/>
Open JDK For Ubuntu
<br/>
<b> $ </b> sudo apt update
<br/>
<b> $ </b> sudo apt install default-jdk

# Install MAVEN
Make sure MAVEN is installed in the system.
<br/>
https://maven.apache.org/
<br/>
Maven For Ubuntu
<br/>
<b> $ </b> sudo apt-get install maven

# Build
Please clone the project and navigate to the project.
<br/>
<b> $ </b> mvn clean package -DskipTests=true

# Run
<b> $ </b> java -jar target/dhee-widget-examples-0.0.1-SNAPSHOT.jar
