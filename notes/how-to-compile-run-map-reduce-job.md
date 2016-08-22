# How to compile and run a map reduce program - Hadoop MapReduce

```sh
javac -classpath $(hadoop classpath) Traffic.java
jar cf Traffic.jar Traffic*.class
hadoop jar Traffic.jar Traffic /user/hduser/input /user/hduser/output
```
