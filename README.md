# Archetype for creating Vaadin widget add-ons

_To try this out:_

git clone https://github.com/jojule/vaadin-archetype-widget.git

cd vaadin-archetype-widget

Comment out properties-maven-plugin and maven-gpg-plugin from the pom.xml

mvn install

cd ..

mvn archetype:generate -DarchetypeGroupId=com.vaadin -DarchetypeArtifactId=vaadin-archetype-widget -DarchetypeVersion=7.0-SNAPSHOT
