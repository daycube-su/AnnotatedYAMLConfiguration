
## Maven

```
<repository>
    <id>repo.daycube.su</id>
    <url>https://repo.daycube.su/releases</url>
</repository>

<dependency>
    <groupId>ru.leymooo</groupId>
    <artifactId>AnnotatedYAMLConfiguration-bukkit</artifactId>
    <version>1.2-SNAPSHOT</version>
</dependency>
```

## Gradle

```
maven {
    url = uri("https://repo.daycube.su/releases")
}

implementation("ru.leymooo:AnnotatedYAMLConfiguration-bukkit:1.2-SNAPSHOT")
```