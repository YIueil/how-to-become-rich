### Usage

Add the following to `pom.xml`:

```
<project ...>

    ...

    <repositories>
        <repository>
            <id>github-rich-repo</id>
            <name>YIueil's Repository on Github</name>
            <url>/maven-repo/</url>
        </repository>
    </repositories>

    <dependencies>
        <dependency>
            <groupId>cn.yiueil.how-to-become-rich</groupId>
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
