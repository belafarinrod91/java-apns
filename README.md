fixed eclipse project notnoobs java apns 

Using notnoop's java-apns (https://github.com/notnoop/java-apns) with
GAE/J 

- fixed Security Exception for GAE, concerning multithreading
- fixed pom.xml, so 'mvn compile' oder eclipse can build the project

Instructions :

1) import project with eclipse maven plugin 

2) build it or build it with 'mvn compile' 

3) add target.jar as lib to your GAE/J backend
