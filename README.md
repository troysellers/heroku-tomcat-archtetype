# Heroku Tomcat Archetype

This library is currently designed to be installed locally, creating a maven archetype that can generate a skelton Java app for deployment to Heroku.

To use, first clone this repository ... 
then

```
> mvn clean install
```
This will build and install the archetype into your local repository.

Then, change into the directory you want to create you application in and

```
>mvn archetype:generate \
    -DarchetypeGroupId=com.troy-sellers \
    -DarchetypeArtifactId=heroku-tomcat \
    -DarchetypeVersion=1.2-SNAPSHOT \
    -DgroupId=<your group id> \
    -DartifactId=<your artifact id>
```
