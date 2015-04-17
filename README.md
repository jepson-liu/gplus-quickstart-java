# Google+ Java Quickstart

Prepare
-------
Copy/paste client_secrets.json.example to client_secrets.json

Compile
-------
```
mkdir bin
javac -sourcepath src -d bin -classpath "lib/*" src/com/google/plus/samples/quickstart/Signin.java
```

Run
---
```
java -classpath "bin:lib/*" com.google.plus.samples.quickstart.Signin
```
.. then browse http://localhost:4567