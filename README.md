# ReplCalculator

### What

This is a basic REPL calculator. The calculator itself is not very interesting (supports plus, minus, times, divide, power, braces). But it is created using JavaCC

### How to run

- Install Java if you haven't already
- Install JavaCC (manual process described [here](https://javacc.java.net/doc/installhelp.html).)
  - If you install JavaCC 6.0, you will find that the executables in /bin are missing. Grab them from the JavaCC 5.0 version, they are the same.
- Run the following to generate parser code:

```
$ javacc src -OUTPUT_DIRECTORY=.\generated .\src\main\calculator.jj
```

- compile and run java code as normal
