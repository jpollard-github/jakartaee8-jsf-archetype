# Jakarta EE 8 JSF Maven Archetype

A quickstart Maven archetype for creating JSF 2.3 projects for application servers.

# Usage
Substitute your desired version, groupId, and artifactId.

`mvn archetype:generate -DarchetypeGroupId=com.jason-pollard -DarchetypeArtifactId=jakartaee8-jsf-archetype -DarchetypeVersion=0.0.1-SNAPSHOT -Darchetype.interactive=false --batch-mode -Dversion={version} -DgroupId={groupId} -DartifactId={artifactId}`

For example:

`mvn archetype:generate -DarchetypeGroupId=com.jason-pollard -DarchetypeArtifactId=jakartaee8-jsf-archetype -DarchetypeVersion=0.0.1-SNAPSHOT -Darchetype.interactive=false --batch-mode -Dversion=0.0.1-SNAPSHOT -DgroupId=com.awesomecorp -DartifactId=awesome-project`

