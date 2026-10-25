This is a very ambitious and definitely not temporary project

## Hello World (Kotlin)

Run with the Gradle wrapper (no local Gradle install needed):

```sh
./gradlew run        # Windows: gradlew.bat run
```

The build compiles against a JDK 21 toolchain. If JDK 21 is not installed,
Gradle downloads one automatically through the foojay toolchain resolver.

Or with the Kotlin compiler directly:

```sh
kotlinc src/main/kotlin/Main.kt -include-runtime -d hello.jar
java -jar hello.jar
```
