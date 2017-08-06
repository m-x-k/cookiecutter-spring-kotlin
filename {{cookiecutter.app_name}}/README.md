# {{cookiecutter.project_name}}

# Requirements

* JDK version 8+
* Kotlin version 1.0.5 (see build.gradle)

## Compile and run tests

```
./gradlew clean build test
```

## IDE Setup

### Intellij

```
./gradlew cleanIdea idea
```

### Eclipse

```
./gradlew cleanEclipse eclipse
```

## Run the application
```
./gradlew bootRun
```

In a browser go to `http://localhost:8080/`.
