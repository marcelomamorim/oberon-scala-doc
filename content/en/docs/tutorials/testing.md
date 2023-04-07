---
title: "Testing"
description: "How to test"
lead: "How to test"
date: 2020-10-13T15:21:01+02:00
lastmod: 2020-10-13T15:21:01+02:00
draft: false
images: []
menu:
  docs:
    parent: "prologue"
weight: 130
toc: true
---

## Testing documentation

Adding new unit test:

1. Go to folder ::::> src/test/scala
2. Choose arithmetic test folder ::::> src/test/scala/br/unb/cic/oberon/arithmetic
3. Open file 'ArithmeticTest.scala'

```markdown

  test("Describe what is your test function") {
    val i10 = IntValue(10)
    val i5 = IntValue(5)

    val expectedResult = IntValue(5)

    assert(expectedResult == (i10 - i5))
  }

```

Run test. If it doesn't work very well, check out the video tutorial, it may help you:

...
## Testing sample

![new test](/images/adding-unit-test.gif)

