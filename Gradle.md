# Gradle

#### Refreshing all dependencies

```
./gradlew build --refresh-dependencies
```

#### Updating gradle wrapper

```
./gradlew wrapper --gradle-version <version> --distribution-type [all|bin]
```

#### Profiling with report in (build/reports/profile)

```
./gradlew app:assembleDebug --profile
```
