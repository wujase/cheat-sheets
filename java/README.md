# Overview

- [java](https://docs.oracle.com/javase/8/docs/technotes/tools/windows/java.html)

# Cheat Sheets

| Command                               | Description | Note |
|---------------------------------------|-------------|------|
| `java [options] classname [args]`     |             |      |
| `java [options] -jar filename [args]` |             |      |

| Standard Option                | Description                                                                                                                                                                                                                                                                                                   | Note                                   |
|--------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------|
| `-Dproperty=value`             | Set a system property value. The property variable is a string with no spaces that represents the name of the property. The value variable is a string that represents the value of the property. If value is a string with spaces, then enclose it in quotation marks.                                       | e.g. `-Dspring.profiles.active="prod"` |
| `-javaagent:jarpath[=options]` | Load the specified Java programming language agent. For more information about instrumenting Java applications, see the java.lang.instrument package description in the Java API documentation at [java.lang.instrument](http://docs.oracle.com/javase/8/docs/api/java/lang/instrument/package-summary.html). | e.g. `-javaagent:dd-java-agent.jar`    |

| Non-Standard Option | Description                                                  | Note             |
|---------------------|--------------------------------------------------------------|------------------|
| `-Xms[size]`        | Set the minimum and the initial size (in bytes) of the heap. | e.g. `-Xms1024m` |
| `-Xmx[size]`        | Set the maximum size (in bytes) of the heap.                 | e.g. `-Xms4g`    |
| `-Xss[size]`        | Set the stack size (in bytes) of the thread.                 | e.g. `-Xss512k`  |

| Advanced Serviceability Option    | Description                                                                                                                                                        | Note                                        |
|-----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------|
| `-XX:+HeapDumpOnOutOfMemoryError` | Enable the dumping of the Java heap to a file in the current directory by using the heap profiler (HPROF) when a `java.lang.OutOfMemoryError` exception is thrown. |                                             |
| `-XX:HeapDumpPath=[path]`         | Set the path and file name for writing the heap dump provided by the heap profiler (HPROF) when the -XX:+HeapDumpOnOutOfMemoryError option is set.                 | e.g. `-XX:HeapDumpPath=/temp/heap-dump.log` |
