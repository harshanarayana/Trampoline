# Trampoline

### Description

Welcome to **Trampoline**.

Are you developing an application based on the _paradigm of microservices_ using spring boot? Are you **tired of that set of scripts**? Quiet, Trampoline has come in your life.

The aim is to **help during the course of developing an application based on the paradigm of microservices with _spring boot nature_**. How? Easy, thanks to a **comfortable interface** you can **declare new microservices**, **starting instances** and **kill them**.

Also you will be able to:
* Configurable Actuator endpoint & VM arguments
* Monitor memory usage for each instance, capturing their metrics every 30 seconds.
* Monitor intances trace information any point in time

### Requirements

* Java 8 & Apache Maven
* Start actuator sub-project of Spring Boot on your microservices
* Set up logging.path property your microservices in order to be able to visulize them

### How do I make it work?

1. You just have to start the project trampoline and start it with the well known command mvn spring-boot:run. 
2. Once started, go to [localhost:8080](http://localhost:8080). 
3. Once there, the only thing you should do is enter the path to your apache maven. 
4. Finally you just have to declare your microservices and to start and/or to stop them as you wish.

### FAQ
* How does the UI look like?

![Alt text](https://github.com/ErnestOrt/Trampoline/blob/master/TrampolineUI.png)

* I am working with Spring Boot 1.3 or less and instances do not start.

You should add security starter on your microservices pom.xml:

```
<dependency>
	<groupId>org.springframework.boot</groupId>
	<artifactId>spring-boot-starter-security</artifactId>
</dependency>

```

* Can I run it on any OS?.

Theoretically yes, but only has been fully tested on Windows and Mac OS.

* Will I have to enter data all the time?.

No, information introduced will be stored in a settings file, next to the script to launch each microservices :grin:

### Contributing
Start with clicking the star button to make the author and his neighbors happy :blush:. Then fork the repository and submit a pull request for whatever change you want to be added to this project.

If you have any questions, just open an issue.

# Enjoy it Folks!
