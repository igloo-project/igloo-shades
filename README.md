# igloo-shades
Shaded jars for Igloo

# How to update Igloo version

Note : The project's version follows Igloo's version

* Clone the project
* Update every `pom.xml` except the parent

```
mvn versions:set versions:commit -DnewVersion=<desired Igloo version>
```

* Update the parent `pom.xml` : update `<version>` and `<igloo.version>` with the desired Igloo version
* Check the diff, commit and push, this project is mirrored in GitLab
