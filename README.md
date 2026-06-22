Maven Learnings

This repository contains my learning of Apache Maven, including pom.xml, dependency management, and project creation using Maven archetypes.

What I Learned:
1.What Maven is and why it is used
2.Structure and role of pom.xml
3.Dependency management using Maven Central
4.Maven Archetypes for project setup
5.Understanding GAV (GroupId, ArtifactId, Version)


📁 Project Structure:

Standard Maven project layout with:

src/main/java for source code
src/test/java for test code
pom.xml for configuration

POM.xml Overview:
pom.xml is the core file of a Maven project. It defines project details (GAV), dependencies, and build configuration.

GAV Concept:
Each Maven project is uniquely identified by:

GroupId : ArtifactId : Version
Example: com.example.maven : maven-basics : 1.0-SNAPSHOT

Maven Archetype:
Used Maven archetype to quickly generate a standard project structure with default configuration.