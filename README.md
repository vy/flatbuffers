According to the [official FlatBuffers project](https://github.com/google/flatbuffers),

> FlatBuffers is a serialization library for games and other memory
> constrained apps. FlatBuffers allows you to directly access serialized
> data without unpacking/parsing it first, while still having great
> forwards/backwards compatibility.

Unfortunately, FlatBuffers project does not publish any artifacts
to the Maven Central Repository. In this fork, I keep a separate
and intact copy of the FlatBuffers Java API for the purpose of
publishing artifacts.

Usage
=====

You can use this fork of the FlatBuffers Java API with the following
Maven dependency:

```xml
<dependency>
    <groupId>com.vlkan</groupId>
    <artifactId>flatbuffers</artifactId>
    <version>1.2.0-3f79e055</version>
</dependency>
```

The latest version of FlatBuffers is 1.2.0-SNAPSHOT and does not
have a release version yet. In order to the report the version of
the clone, I prepend the first 8 digits of the most recent commit
I had used to produce the artifact.

License
=======

As is the case for the official FlatBuffers repository, this fork is
also licensed under the terms of Apache License, Version 2.0.
