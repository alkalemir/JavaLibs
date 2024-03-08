# Java Libs

To install a lib you can use this ***mvn*** command.

```bash
mvn install:install-file -DgroupId=dev.emir -DartifactId=dev-emir-hellolib -Dversion=1.0.0 -Dfile=../jars/dev-emir-hellolib-1.0.0.jar -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=. -DcreateChecksum=true
```