# C++ Programming Exercises

A collection of small programs and working notes exploring core C++ problem-solving techniques. The files record successive approaches to number conversion, recursion, arrays and elementary algorithms.

## Explore by topic

| Topic | Examples |
|---|---|
| Number systems | `Converter`, `Update on converter`, `Any base converter ( up till 36 )` |
| Recursion | `Recursion and reverse`, `Reverse recursion` |
| Arrays | `Enter array copy array`, `Transposition of an array` |
| Number/string checks | `Some prime checkers`, `Curious palindrome checker :)` |
| Language practice | `Class notes`, tutorial and contest files |

The base-conversion variants are useful for following an idea through several revisions. Compare their input handling, digit construction and assumptions about valid numbers and bases.

## Compile one program

The source files have descriptive names without a `.cpp` extension. For a standalone file containing `main`, tell the compiler which language to use:

```bash
g++ -x c++ "Any base converter ( up till 36 )" -o base_converter
```

Run the resulting executable and follow its terminal prompts. On Windows use `./base_converter.exe`; on macOS/Linux use `./base_converter`.

Compile files individually. This repository is a collection of exercises and notes, not one linked application; some files may need cleanup or contain multiple exploratory fragments.

## Reading the collection

Start with a small input whose answer you can calculate manually, then inspect boundary cases such as zero, negative numbers and unsupported bases. The programs use exercise-specific assumptions and are not a production conversion or mathematics library.

The collection documents programming fundamentals and progression; it is complementary to the more applied research and application projects elsewhere in the portfolio.
