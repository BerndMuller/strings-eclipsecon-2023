# Examples for string implementations details


## Run the Tests
```
mvn clean test-compile surefire:test@encoding
mvn clean test-compile surefire:test@deduplication
mvn clean test-compile surefire:test@pool

mvn antrun:run@table-statistics
```

## Run Applications
```
java -XX:-CompactStrings --add-opens java.base/java.lang=ALL-UNNAMED de.pdbm.CompactStrings
```



## JavaDoc
```
mvn javadoc:test-javadoc
```


