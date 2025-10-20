READ ME FILE

REFACTOR SUMMARY

Code was refactored to use lambda expressions in place of for loops and comparison functions. Most expressions make use of the filter and map methods in relevant ways, but I have also made use of: Reduce, Distinct, Flatmap, and Comparator.comparing. The code in this state is more scalable as lambda expressions allow for easier to read, highly controllable code- with the workflow of the program being made clearer. Also, using lambda expressions removed the issue of heavily nested for and if statements- which were used throughout this program. Lastly, I was unable to find any major performance difference between the two methods- sometimes one was faster sometimes the other was faster. However, under the hood- using Lambda Expressions is still much better for the advantage of readability.

SIMULATED PEER REVIEW

Overall the original code was effective if what it set out to do. There was substantial exception handling, use of higher-level functions like comparators, and the code was separated into a relatively easy to follow format. However, much of the code was harder to read due to the use of frequent -and often even nested several times over- if and for statements. However, after implementing lambda expressions, many of the longest functions were reduced to substantially smaller line counts. The program still does the same thing as before, but in a more manageable way. All of my refactors were done with the goal of reducing the length of the code as much as possible, and to also simplify wherever I could as well.

NOTES:

Before and After is with comment blocks showing the original code following the refactored coding segments. Refactored code is in the refactored code file, original code is in the base code file.