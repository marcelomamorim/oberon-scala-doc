---
title: "Quick Start"
description: "One page summary of how to start."
lead: "One page summary of how to start."
date: 2020-11-16T13:59:39+01:00
lastmod: 2020-11-16T13:59:39+01:00
draft: false
images: []
menu:
  docs:
    parent: "prologue"
weight: 110
toc: true
---

## Requirements

- [git](https://git-scm.com/) — latest source release
- [jdk](https://jdk.java.net/11/) — latest LTS version or newer
- [sbt](https://www.scala-sbt.org/1.x/docs/Installing-sbt-on-Linux.html)

{{< details "Why Jdk, Git and Sbt?" >}}

As written in Scala Doc (https://docs.scala-lang.org/overviews/jdk-compatibility/overview.html):
"Scala’s primary platform is the Java Virtual Machine (JVM)".

We use Git to versioning.

Sbt is a build tool (doc) for Scala. Similar to Maven in Java context and Npm for Javascript.
See their doc: https://www.scala-sbt.org/1.x/docs/Howto-Scaladoc.html

{{< /details >}}

## Installing requirements

#### Git
``` bash
 sudo apt install git-all
```

#### Jdk
``` bash
 sudo apt install default-jdk
```

#### Sbt (first install SDKMAN ::> https://sdkman.io/install)
``` bash
sdk install sbt
```

## Optional to install

- Intellij (IDE): You can use any IDE
- Intellij Plugin For Scala 


## Compile the project

``` bash
sbt clean compile
```

## Run tests
``` bash
sbt test
```

## Generate executable (.jar) file
``` bash
sbt assembly
```

See full documentation here: https://github.com/UnBCIC-TP2/Oberon-Scala/blob/master/README.md