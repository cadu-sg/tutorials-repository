**Clean**
```
rm -rf classes/*
```

**Compile** (option 1)
```
javac -d classes $(find sources -name "*.java")
```
**Command** (option 2, works the same and I don't know the difference)
```
javac -d classes --source-path sources $(find sources -name "*.java")
```

**Run**
```
javac --source-path sources/ -d classes/ sources/cadu/baeldung/Main.java
```

**Links**
- https://www.baeldung.com/javac-compile-classes-directory
- https://docs.oracle.com/javase/tutorial/java/package/managingfiles.html
