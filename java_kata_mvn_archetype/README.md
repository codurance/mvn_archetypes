Java Kata Maven Archetype
=========================

Contains basic libraries like junit, hamcrest, mockito, cucumber-jvm, etc.

It also provides the correct folder structure, with empty production and test classes.

To install this archetype into your local maven repository, In the root folder of this project, type:

    mvn install

To use it, create a new maven project in your IDE, selecting the archetypes option. If you just installed this archetype, you will need to add it to your IDE providing the following information:

    GroupId: com.codurance
    ArtifactId: java_kata_mvn_archetype
    Version: 1.0-SNAPSHOT

You just need to do it once. Next time you create a project, you just need to select this archetype and you are done.

Have a look at [maven archetypes](http://maven.apache.org/guides/mini/guide-creating-archetypes.html) for more information.
