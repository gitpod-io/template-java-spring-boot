# A Spring Boot Java template on Gitpod

[Spring Boot](https://spring.io/) is a Java framework for developing web applications. This is a Spring Boot template using Java 11 and [Maven](https://maven.apache.org/) configured for cloud development environments on [Gitpod](https://www.gitpod.io/).

## Next Steps

Click the button below to start a new development environment:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/gitpod-io/template-java-spring-boot)

### How to run this project 

To run the project on Gitpod IDE, select "Run and Debug" from the left sidebar and select "Java" in the pop-up. Wait for the project to compile and open the preview environment. 

### Using Jetbrains Gateway 

Jetbrains Gateway is a desktop app that allows you to work remotely with a Jetbrains IDE (such as IntelliJ IDEA) without installing it on your machine. 

To run this project on Jetbrains Gateway: 
- Setup Gitpod integration with Jetbrains Gateway using the instructions in this [doc](https://www.gitpod.io/docs/ides-and-editors/intellij).
- Open Jetbrains Gateway in your machine, and under the Gitpod tab, connect to your workspace. If you have already configured Jetbrains Gateway with Gitpod, it will automatically open an IDE window with this project. 
- Wait for IDEA to import the project and select "Run" from the toolbar to start the application. Once port `8080` is online, click on the port to forward it to your local machine and open it in your browser. 
- You can also run `./mvnw spring-boot:run` in the IDEA terminal to start the project. 

## Get Started With Your Own Project

### A new project

Click the above "Open in Gitpod" button to start a new workspace. Once you're ready to push your first code changes, Gitpod will guide you to fork this project so you own it.

### An existing project

To get started with Spring Boot on Gitpod, add a [`.gitpod.yml`](./.gitpod.yml) file which contains the configuration to improve the developer experience on Gitpod. To learn more, please see the [Getting Started](https://www.gitpod.io/docs/getting-started) documentation.
