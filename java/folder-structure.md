# Folder structure for Java projects
I use [Maven](https://maven.apache.org/) for all my Java projects. Therefore, for the most part I'm using Maven's default folder structure.

| Folder | Contents
| :-- | :--
`/` | Repository files, such as readme, licenses and main `.gitignore`. Also the Maven POM file and additional build setting files.
`/docs` | Generated Javadoc.
`/lib` | Libraries that aren't in a Maven repository and thus need to be imported locally into Maven.
`/src/main/java` | Source code.
`/src/main/resources` | Resources, such as config files, databases and images.
`/src/tests/java` | Source code for tests.
`/src/tests/resources` | Resources for tests, such as config files, databases and images.
`/target` | Generated files from build processes etc.
