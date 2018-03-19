Panera API Archtetype

This project is a maven Archetype to help developers start with a base SpringBoot Starter project
with default Directory Structures and config setup

command :

mvn archetype:generate -DarchetypeCatalog=local 
-DarchetypeArtifactId=<new-app-Artifact-name>
-DarchetypeGroupId=<new-app-group-id>
 -DarchetypeVersion=<version>

ex :
mvn archetype:generate -DarchetypeCatalog=local 
-DarchetypeArtifactId=panera-api-archetype 
-DarchetypeGroupId=com.panera.api.archetype
 -DarchetypeVersion=0.1-SNAPSHOT


mvn archetype:generate -DarchetypeCatalog=local -DarchetypeArtifactId=Test-ArcheType -DarchetypeGroupId=com.MyCompany.archetype  -DarchetypeVersion=1.0-SNAPSHOT