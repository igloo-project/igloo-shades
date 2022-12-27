
# DO NOT USE - This project is no longer used

# igloo-shades

Shaded jars for Igloo

# How to update Igloo version

Note : The project's version follows Igloo's version

* Clone the project
* Update project version

```
mvn versions:set versions:commit -DnewVersion=<desired Igloo version>
```

* Update the parent `pom.xml` : update `<version>` and `<igloo.version>` with the desired Igloo version
* Project is ready for maven deployment
