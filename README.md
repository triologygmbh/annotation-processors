# annotation-processors

An example on how to use Java Annotation Processors.

## Part 1

The source folder **part-1** contains an intro example for the use of Java Annotation Processors. To test the example, you will need an installed JDK 8.

Compile the Annotation Processor:

```
javac –cp . -proc:none de/triology/blog/annotationprocessor/log/*.java
```

Compile the Hello class:

```
javac –cp . de/triology/blog/annotationprocessor/sample/Hello.java
```

Durring the compilation of the Hello class, you should see an output from the Annptation Prozessor like the following:

```
Note: found @Log at de.triology.blog.annotationprocessor.sample.Hello
```