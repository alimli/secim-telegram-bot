
```
jenv shell 11.0
jenv exec  mvn org.apache.maven.plugins:maven-archetype-plugin:3.1.2:generate -DarchetypeArtifactId="maven-archetype-quickstart" -DarchetypeGroupId="org.apache.maven.archetypes" -DarchetypeVersion="1.4" -DgroupId="cloud.upandrunning" -DartifactId="secim-telegram-bot" 
cd secim-telegram-bot
jenv local 11.0
```
