# scala-xtend-gradle

This repository contains two sets of projects.

## gradle-projects

Building the code from Gradle works:

```
./gradlew build
```

However, the code does not compile in Eclipse, with the Xtend and Scala IDEs installed.

A possible workaround is to wrap the Scala class to a Java class and use it from Xtend.

## plain-eclipse-projects

These are plain Eclipse projects (i.e. do not use Maven or Gradle), but still do not work, which implies that the errors is not due to a limitation in Buildship/Gradle.
