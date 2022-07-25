### Usage

Add the following to `pom.xml`:

```
<project ...>

    ...

    <repositories>
        <repository>
            <id>github-rich-repo</id>
            <name>YIueil's Maven Repository on Github</name>
            <url>https://yiueil.github.io/how-to-become-rich/maven-repo/</url>
        </repository>
    </repositories>

    <dependencies>
        <dependency>
            <groupId>cn.yiueil</groupId>
            <artifactId>how-to-become-rich</artifactId>
            <version>0.0.1</version>
        </dependency>
    </dependencies>

    ...

</project>
```

### Sample code

```
System.out.println(Author.NAME);
```
