## Useage
```xml
<repositories>
    <repository>
        <id>maven-repository-main</id>
        <url>https://raw.github.com/langkye/maven-repository/main/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>

 <dependencies>
    <dependency>
          <groupId>${groupId}</groupId>
          <artifactId>${artifactId}</artifactId>
          <version>${version}</version>
    </dependency>
</dependencies>
```
