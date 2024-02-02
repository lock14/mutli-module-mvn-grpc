## Linux/MacOS
```shell
$ ./mvnw clean install
$ ./mvnw exec:java -pl application -Dexec.mainClass="org.example.grpc.App" 
```

## Windows
```shell
> ./mvnw.cmd clean install
> ./mvnw.cmd exec:java -pl application -Dexec.mainClass="org.example.grpc.App" 
```
