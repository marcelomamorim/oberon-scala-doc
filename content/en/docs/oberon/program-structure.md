---
title: "Program Structure"
description: "Basic structure of a Oberon program."
lead: "Basic structure of a Oberon program."
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  docs:
    parent: "oberon"
weight: 130
toc: true
---

# First Example

Let's take one of the programs written at our compile in folder 'src/test/resources'.

```markdown

MODULE SimpleModule;

VAR
  x : LONGINT;
  y : SHORTINT;
BEGIN
    x := 5000;
    y := 7;
    x := x * y;
    x := x / y;
    x := x + y;
    x := x - y
END

END SimpleModule.

```

We can try to make a basic structure like this:

```markdown

MODULE {{ModuleName}};

VAR
  x : {{TYPE}};
  y : {{TYPE}};
BEGIN
    x := {{VALUE}};
    y := {{VALUE}};
END

END {{ModuleName}}.

```

As you can see, there is some reserved terms like:

- MODULE
- VAR
- BEGIN
- END