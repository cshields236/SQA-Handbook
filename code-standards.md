
# Coding Standards

## Introduction

Many software companies use coding standards for their programmers to maintain a well-defined and standard style of code.
Programmers should adhere to these coding standards, which are a set of rules and defined guidelines, sets of best practices, programming styles and established conventions when writing code.

Why to use coding standards?

- A coding standard gives a uniform appearance to all the code written by different engineers.
- Improve readability and reduces complexity.
- Help in code reusability and to detect errors easily.
- Promote sound programming practices and increase the efiiciency of programmers.

## Most common coding standards and conventions

**1.** **Limited use of global variables**

- This standard states which variables and data types should be declared globally and which not.

- For example, variables that are accessed only from a method must be local variables of this method not the whole class. (Shown in the below two figures)

    _Global variable bad practice_

    ![Getting Started](images/1.png)

    _Global variable good practice_

    ![Getting Started](images/2.png)

**2.** **Naming conventions for local variables, global variables, constants**

- Short, meaningful and understandable variables name make it easier for the reader to understand its purpose, names to be self-explanatory and not require a guide or working knowledge.

- Local variables should be name using camel case lettering starting with lowercase letters and constant names should be formatted using all capital letters.

- Variables names should not contain digits.

- Functions/methods should be written in camel case starting with small letter.

- Names used for functions/methods should be meaningful and relatively short.

- The usage of and identifier for multiple purposes should be avoided by giving a descriptive name.

- Class names should be written in Upper Camel Case and by using nouns or noun phrases.

- One-character parameter names in public methods should be avoided.

**3.** **Indentation and spacing standards**

Proper indentation is very important to increase the readability of the code. For making the code readable, programmers should use White Spaces properly as follows.

- There must be a space after comma between two function arguments.

- Nested blocks should be properly indented and spaced.

- Proper indentation should be there at the beginning and at the end of each block in the program.

- Braces should follow the _"Egyptian brackets"_ style: no line break before the opening brace, line break after the opening brace and before and after the closing one. (Example shown below)

    _Indentation  good practice_

    ![Getting Started](images/3.png)

    _Indentation  bad practice_

    ![Getting Started](images/4.png)

**4.** **Error return values and exception handling conventions**

- All functions that encountering an error condition should return either a 0 or 1 for simplifying the debugging.
- Exceptions that are caught should not be  ignored.
- A programmer should not catch broad exceptions like   Exception or Runtime Exception

    _Exception handling bad practice_

    ![Getting Started](images/5.png)

    _Exception handling good practice_

    ![Getting Started](images/6.png)

**5.** **Code should be well documented and block comment style should be used**
  
- Programmers should leave comments explaining their code's purpose. Comments regarding statements make them easier to understand.  
- Block comments should be indented at the same level as the surrounding code. They may be in /* ... */ style or // ... style. For multi-line /* ... */ comments, subsequent lines must start with *aligned with the* on the previous line.
- At the same time a developer should avoid leaving comments that are too long or unnecessary.
  
    _Well documented code_

    ![Getting Started](images/7.png)

## Resources

[https://google.github.io/styleguide/javaguide.html](https://google.github.io/styleguide/javaguide.html)

[https://www.geeksforgeeks.org/coding-standards-and-guidelines/](https://www.geeksforgeeks.org/coding-standards-and-guidelines/)

[https://levelup.gitconnected.com/write-better-code-with-coding-standards-546faf3fd4d1](https://levelup.gitconnected.com/write-better-code-with-coding-standards-546faf3fd4d1)

[https://codeahoy.com/2016/05/22/effective-coding-standards/](https://codeahoy.com/2016/05/22/effective-coding-standards/)

[https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/](https://www.multidots.com/importance-of-code-quality-and-coding-standard-in-software-development/)

[https://www.castsoftware.com/glossary/coding-in-software-engineering-best-practices-good-standards](https://www.castsoftware.com/glossary/coding-in-software-engineering-best-practices-good-standards)
