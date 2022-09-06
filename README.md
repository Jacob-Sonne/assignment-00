# Assignment 0

These exercises are meant to get you familiar with the tools used during the course.

The C# part of the course will use Visual Studio Code on Windows primarily but you should be able to complete all exercises using either macOS or Linux.


## Exercise 1 - C# Hello, World

(Do this after the first C# lecture)

TODO: What is the actual exercise here?

## Exercise 2 - Boiler plate

Using the shell of your choice:

1. Create a new public repository on GitHub with README, .gitignore, and license.
1. Clone repository to your local machine
1. Create a solution file and add a GitHub action to validate builds
1. Push changes
1. Configure branch protection and squash merging on GitHub.
1. Checkout new branch
1. Create a C# console application project
1. Create an xunit test library project
1. Reference the console app from the test library
1. Create a solution file and add the two projects
1. Make sure everything runs using:

   ```bash
   dotnet build
   dotnet run
   dotnet test
   ```

1. Commit your code and create pull request
1. Merge changes

## Exercise 3 - Leap year function

A leap year in the Gregorian calendar is defined by the following rules (simplified):

> Every year that is exactly divisible by four is a leap year, except for years that are exactly divisible by 100, but these centennial years are leap years if they are exactly divisible by 400. For example, the years 1700, 1800, and 1900 are not leap years, but the years 1600 and 2000 are.

Your function should have the following signature:

```csharp
bool IsLeapYear(int year)
```

Implement the function iteratively using Test-Driven Development where first write a set of tests for the first rule (divisible by four) and then implement the rule.

Continue with the subsequent rules in the same fashion.

**Integrate your changes on GitHub** with a commit message like *Tested and implemented IsLeapYear*.


## Exercise 4 - User input

When you run your console app the user should be prompted to type in a year and hit `[Enter]`.

Your program should respond accordingly with a `yay` or `nay` whether it's a leap year or not.

Implement the requirements for the console app. If you are up for it write the tests first here as well.

**Integrate your changes on GitHub** with a commit message like *Created user interface for IsLeapYear*.


## Exercise 5 - Error handling

Consider how you want to handle errors.

The leap year function should only apply to years from 1582.

How will you handle if a user inputs something which is not convertible to an integer?

Extend your program with a number of tests and implement your error handling.

**Integrate your changes on GitHub** with a commit message like *Implemented error handling*.


## Exercise 6 - Documenting code

Use your favorite diagram drawing tool and your favorite modeling language to draw a diagram that visualizes the algorithm that you implemented in the `IsLeapYear` function above.


## Exercise 7 - LaTeX

Create a PDF document using LaTeX in which you embed the diagram created in exercise 6. 
In that document you describe in prose the illustrated algorithm.

**Integrate your changes on GitHub** with a commit message like *Added documentation*.

## Submission

Before Friday 9/9/22 10:00, you submit a link to your public GitHub repository that contains all source code, the LaTeX sources, built PDF, etc. to [LearnIT](https://learnit.itu.dk/mod/assign/view.php?id=163682).