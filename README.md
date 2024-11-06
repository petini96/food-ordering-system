# Ordering Java System

It's for my study. From teacher @agelenler 

- DDD
- Hexagonal Arch
- SAGAS / Outbox pattern

### Github to download dependency graph lib
```bash
https://github.com/ferstl/depgraph-maven-plugin
```

### Command for generate dependency graph
```bash
  mvn com.github.ferstl:depgraph-maven-plugin:aggregate -DcreateImage=true -DreduceEdges=false -Dscope=compile "-Dincludes=com.food.ordering.system*:*"
```