---
title: "Compiling"
description: "How to run compile command."
lead: "How to run compile command."
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  docs:
    parent: "tutorials"
weight: 130
toc: true
---

## Executando compição

1 - Uma opção de compilação:

```

compile -b jvm -i /home/bits/Documents/github-repos/unb/Oberon-Scala/src/test/resources/stmts/loop_stmt01.oberon -o /home/bits/Documents/github-repos/unb/Oberon-Scala/output/output-loop.class

```

2- Outra opção:

```

compile -b c -i /home/bits/Documents/github-repos/unb/Oberon-Scala/src/test/resources/procedures/procedure03.oberon -o /home/bits/Documents/github-repos/unb/Oberon-Scala/output/bytecode.c 

```

3 - Detalhando:

Podemos escolher qual backend iremos selecionar passando o parâmetro '-b' (c, jvm, llvm).
