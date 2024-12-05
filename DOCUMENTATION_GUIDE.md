# DOCUMENTATION GUIDE

__This guide represents my opinion how a good documentation should look like and is a reference for my projects.
This guide does not apply to all projects on github. 
Please read the documentation on the forked/cloned repo and follow the rules for the specific repo.__

## Introduction

How code should be documented, knows every software vendor and programmer. But checking repositories
on github, you often don't find documentation or comments in the code.

If you contribute to any of my projects, you have to stick to these guidelines, otherwise your pull requests won't be merged.

All code examples consist of pseudocode or contain a reference, if taken from real code.

## Documentation

A good documentation should at least contain [inline comments](#using-inline-comments) for small projects and a separate [project documentation](#using-project-documentation) in the ***/docs*** folder for bigger projects. 

A documentation should always be readable either via browser or via commandline. The correct character encoding is mandatory. 

Websites and wikis can be created but are not mandatory.

The criteria when a project is considered a bigger project is the number of contributors. If there are more than 3 contributors, a [project documentation](#using-project-documentation) should be created.

### Using inline/multiline comments

There are different types of inline/multiline comments:

1. [Singleline comments](#inline-comments): one line comments, using single comment symbol.
2. [Multiline comments](#multiline-comments): multiline comments, using single comment symbol or multiline 
commend symbol.

*All single line comments should have a blank behind the comment symbol, all multiline comments
a blank and a newline, to enhance readability.*

#### Singleline comments:

[Ref: C++](https://github.com/IT-Administrators/cutpproh/blob/main/src/cutpproh.hpp): Line 65
```c++
char GetCharOnPos(const std::string& strng, const int& pos); // Get char on positon.
```
Singleline comments are either on the same line, or above the code they describe. For example a function or variable. The lenght of inline comments should not be longer than 50 characters and use only one line. 

If you comment a piece of code with more than one line use the [multiline comments](#multiline-comments).

#### Multiline comments:

[Ref: C++](https://github.com/IT-Administrators/cutpproh/blob/main/src/cutpproh.hpp): Line 65
```c++
/*
This function extracts the character on the given
position. 

This is a comment using the multiline commen specifier.
*/
char GetCharOnPos(const std::string& strng, const int& pos);
```

### Using project documentation

A project documentation should always be stored in the ***/docs*** directory of the project root.

This documentation should contain at least the following files: 

1. __Overview__: A file that contains a sum up of all the other items, with a reference to their documentation. The sum up can be a text, but can be more compact if a table is used.
This is an example table. 

    The advantage of this is, that you have every important information at a glance.

    | Classes | Functions / Methods | Variables |
    |---------|---------------------|-----------|
    | [Class One](Reference Url) | [Class One Functions](Reference Url) | [Class One Variables](Reference URL) |
    | [Class Two](Reference Url) | [Class Two Function One](Reference Url), [Class Two Function Two](Reference Url) | [Class Two Variable 1](Reference URL), [Class Two Variable 2](Reference URL), [Class Two Variable 3](Reference URL) |

1. __Classes__: Contains all classes used in the software with a reference to their line of code.
If these classes are used more than once, all references should be shown. 
1. __Functions / Methods__: Contains all functions / methods with a reference to their line of code and a reference to the variables used. 
1. __Variables__: A small overview of all variables.
1. __Build Instructions__: A description how the sofware is build/ compiled.
1. __User Instructions__: A description how the software is used. 

### Using tools

Tools to create a documentation can be handy and have the advantage that the documentation has the same syntax everywhere. All tools that create a documentation should be written in the same language and in the best case, be part of the standard library of the used language. 
The documentation should be created in html or any other browser language and plain text to be readable via a cli. 

The biggest disadvantage is, that there is no tool that creates documentations for all languages. So a lot of parts must be added by hand afterwards, if more than one language is used.