# Role Sheet

It is a project created in an attempt to practice different functionalities that has angular one.
It tries to replicate the specifications that have a role sheet and some of the behaviors given 
by the game so that the user can save their characters in the cloud and be able to use them when required.

## About technologies

RESTful Web Services Application Sample Project with Jersey 1.18.1 and Google Guice 3.0

Dependencies included
---------------------
- Servlet 2.5
- Jersey 1.18.1
- Guice 3.0
- guice-persist 3.0
- gson 2.2.4
- joda-time 2.4
- JUnit 4.10

Requirements
------------
- Java 7
- Maven 3
- Tomcat 7

Building
--------
- Make the war file <code> mvn clean package </code>
- Deploy the war file in Tomcat 7 with Eclipse or manually

After Deploy on Application Server
----------------------------------
- The REST WS are accessible under /rest/*
- Front-End not yet implemented.

Creating a Local Maven Archetype
--------------------------------
- Generate an archetype: <code> mvn archetype:create-from-project </code>
- Go to <code>target/generated-sources/archetype</code> and run <code>mvn install </code>
- Create a fresh project from Archetype <code> mvn archetype:generate -DarchetypeCatalog=local </code> using <code>com.pampanet:jersey-guice-bootstrap-archetype </code>
- From Eclipse you have check the "include snapshot archetypes" checkbox, and select the archetype from the catalog after installing it.
