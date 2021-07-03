---
title: "Model checking from the Command Line"
date: 2021-07-03T12:55:24+02:00
---

You don't need to use the toolbox for model checking.
It is also possible to model check from the command line using `tla2tools.jar`.

Steps to run the model checking from the command line.
 1. Install `java` on the machine
 2. Download the latest `tla2tools.jar` from the [tla releases](https://github.com/tlaplus/tlaplus/releases/latest)
 3. Navigate to the folder the specification is located in
 4. Run `java -cp tla2tools.jar tlc2.TLC SpecName.toolbox/Model_1/MC`

Note that this uses the relative path of `tla2tools.jar` and you have to specify where you downloaded it yourself.

To see all the avaliable options use
`java -cp tla2tools.jar tlc2.TLC -h` 
