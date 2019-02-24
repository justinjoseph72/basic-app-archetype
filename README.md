Creating a basic app archetype

To install the archetype do 

`mvn install archetype:update-local-catalog`

To refresh the catalog do
`mvn archetype:crawl`

To generate a new project using this archetype do 

`mvn archetype:generate \
-DarchetypeGroupId=com.justin.app \
-DarchetypeArtifactId=basic-app-archetype \
-DarchetypeVersion=1.0.0 \
-DgroupId=<your group id> \
-DartifactId=<your artifact id> \
-Dversion=<your version number>
 `