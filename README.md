Example Maven multi-module project
===

With multi-module projects the groupId becomes: com.github.User.Repo
And artifactId remains the same as in the module's pom file.

Module 1:
```xml
   <dependency>
      <groupId>com.github.jitpack.maven-modular</groupId>
      <artifactId>module1</artifactId>
      <version>1.1</version>
    </dependency>
```

Module 2:
```xml
    <dependency>
      <groupId>com.github.jitpack.maven-modular</groupId>
      <artifactId>module2</artifactId>
      <version>1.1</version>
    </dependency>
```

To get both of them together use the usual repository syntax:

```xml
    <dependency>
      <groupId>com.github.jitpack</groupId>
      <artifactId>maven-modular</artifactId>
      <version>1.1</version>
    </dependency>
```
