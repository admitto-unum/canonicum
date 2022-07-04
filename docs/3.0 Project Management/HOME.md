# 3.0 Project Management

# Managing Versions with Maven

Use the following Maven commands to management the project dependencies:


| Description                                           | Maven Command                           |
|-------------------------------------------------------|-----------------------------------------|
| Display build plugins with newer versions             | mvn versions:display-plugin-updates     |
| Display dependencies with newer versions              | mvn versions:display-dependency-updates |
| Update dependencies to latest release                 | mvn versions:use-latest-releases        |


Reference [Versions Maven Plugin](https://www.mojohaus.org/versions-maven-plugin/plugin-info.html)

# Maven Site Reports

Maven site generates the following reports that are used to manage the project dependencies:


| Report                             | Report Location                   |
|------------------------------------|-----------------------------------|
| Project Dependency Management      | site/dependency-management.html   |
| Project Plugin Management          | site/site/plugin-management.html  |
| Project Build Plugins              | site/plugins.html                 |



## Tools

Maven 3.8.6
Jave 1.17
C4 Builder
