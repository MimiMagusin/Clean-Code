# List of Actions Clean Code by Robert C. Martin
> In this repository, you will find a list of actions taken from
[Robert C Martin](https://github.com/unclebob)'s Clean Code. Reading a couple of
chapters, I got a few points out that I tried to implement in my code.

## Chapter 1: Clean Code
  -- Intro --
## Chapter 2: Meaningful Names
* Use intention revealing, pronouncable names.
* Classes and objects should have noun or noun phrase names.
* Method names should have verb or verb phrase names.
* Don't give more information than needed in the context.

## Chapter 3: Functions
* Functions should be as small as possibly makes sense.
* They should only do one thing.
* They should have descriptive names (see Chapter 1).
* They should be monadic or dyadic, but never have more than three arguments.
* Don't repeat yourself!

## Chapter 4: Comments
* Explain yourself in code, rather than in Comments.
* Only use comments in the following cases:
  * Legal comments
  ```
  // Copyright (C) 2003-2004
  ```
  * Warning of consequences
  ```
  // Only run if you have lot's of time on your hands

  ```
  * TODO Comments
  ```
  // TODO: Figure out why this error is not working

  ```
## Chapter 5: Formatting
* Use white space to separate concepts.
* Concepts that are closely related should be placed closely to each other.
* If two functions call each other, they should be placed after each other,
where possible placing the caller above the callee.
* Strive to keep your lines short, max 80-120 characters long.
* Use a space and white space to accentuate assignment operators.
* Parenthesis are use without surrounding spaces.
* Use indentation.
## Chapter 6: Objects and Data Structures
## Chapter 7: Error Handling
## Chapter 8: Boundaries
## Chapter 9: Unit Tests
## Chapter 10: Classes
## Chapter 11: Systems
## Chapter 12: Emergence
## Chapter 13: Concurrency
## Chapter 14: Successive Refinement
## Chapter 15: JUnit Internals
## Chapter 16: Refactoring `SerialDate`
## Chapter 17: Smells and Heuristics
