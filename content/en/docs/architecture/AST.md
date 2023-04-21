---
title: "AST"
description: "Entendendo a Abstract Syntax Tree gerada."
lead: "Entendendo a Abstract Syntax Tree gerada."
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  docs:
    parent: "architecture"
weight: 130
toc: true
---

#### Geração da AST

Abaixo, segue um exemplo de geração de uma Abstract Syntax Tree a partir do seguinte código de um arquivo .oberon (retirado do projeto Oberon-Scala):

```

MODULE SimpleModule;

VAR
  x : REAL;
  y : LONGREAL;
BEGIN
    x := 13.5;
    y := 13.00000000000005
END

END SimpleModule.

```

![Modelo de arquitetura](/oberon-scala-doc/images/ast-generation.png)