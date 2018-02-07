# learnR

## Introduction

learnR is a tutorial for R programming language from basic to advanced levels. It includes basic concepts, motivations, principles and their application in data transformation, data analysis, data mining, statistical computing, financial computing, etc.

## Prerequesites

1. [R](http://cran.rstudio.com/bin/windows/base/)
2. [Rtools](http://cran.rstudio.com/bin/windows/Rtools/)
3. [Rstudio](http://www.rstudio.com/ide/download/preview/)

## Contents

### A: Basic R Programming

1. [Introduction to R programming language](./src/a1.intro.R)
2. [RStudio IDE](./src/a2.rstudio.R)
3. [Basic objects](./src/a3.basic-object-types.R)
    - Vector (Numeric, Integer, Complex, Logical, Character)
    - Matrix
    - Array
    - List
    - Data frame
    - Function
    - Formula
4. [Basic expressions](./src/a4.basic-expressions.R)
    - Assignment expression (`<-`, `<<-`)
    - Conditional expression (`if else`)
    - Loop expression (`for`, `while`)
5. [Basic functions](./src/a5.basic-functions.R)
    - Environment functions
    - Package functions
    - Object functions
    - Logical functions
    - Character functions
    - Math functions
    - Statistical functions
    - Data manipulation (data read/write, transformation)
    - Higher-order functions
    - Optimization functions
    - Anonymous functions
    - Meta-functions
    - Plot functions
6. [Debugging in RStudio](./src/a6.debugging-in-rstudio.R)
7. [Essential statistics](./src/a7-1.essential-statistics.R)
    - Preparing data
    - Descriptive statistics
    - Linear regression
    - [Statistical hypothesis testing](./src/a7-2.hypothesis-testing.R)
    - Model analysis
    - Time series model fit
8. [Essential data mining](./src/a8.essential-data-mining.R)
    - Using models
    - Cross validation
9. [Design patterns](./src/a9.design-patterns.R)


### B: Advanced R Programming

1. [R language mechanism](./src/b1.r-language-mechanism.R)
    - Lazy evaluation
    - Dynamic scoping
    - Object searching
    - Memory management
    - `...`
    - Functions
    - Environment
    - Expression
    - Call
2. [Data structures](./src/b2.data-structures.R)
    - S3 object
    - S4 object
3. [Database](./src/b3.database.R)
    - SQL
    - Read/Write Excel Workbook via `{RODBC}`
    - Read/Write SQLite database via `{RSQLite}`
    - Use SQL to query data frames
4. [Parallel computing](./src/b4.parallel-computing.R)
    - `{parallel}`
    - `{parallelMap}`
    - `{doParallel}` + `{foreach}`
    - `{doParallel}` + `{plyr}`
6. [Functional programming](./src/b5.functional-programming.R)
    - Anonymous functions
    - Closures
    - Higher order functions
7. [Profiling](./src/b6.profiling.R)
    - Computing time tracking
    - Memory use tracking

### C: Popular packages

1. [Popular packages](./src/c1.popular-packages.R)
2. [Read/Write JSON (`{jsonlite}`)](./src/c2.jsonlite.R)
3. [Process strings (`{stringr}`)](./src/c3.stringr.R)
4. [Transform data frame between long and wide formats(`{reshape2}`)](./src/c4.reshape2.R) 
5. [Iterate over vector, list, and data frame (`{plyr}`)](./src/c5.plyr.R)
6. [Handy data frame transformation (`{dplyr}`)](./src/c6.dplyr.R)
7. [Nonlinear root finding (`{rootSolve}`)](./src/c7.others.R)
8. [Nonlinear Optimization (`{Rsolnp}`)
9. [Integrate R with C++ (`{Rcpp}`)](./src/c8.Rcpp.R)
10. [R Markdown Documenting (`{rmarkdown}`)](./src/c9.rmarkdown.R)

### D: [Data Visualization](./src/d1.data-visualization.R)

1. [Basic plots](./src/d2.basic-plots.R)
    - Scatter/line/bar/pie charts
    - Composing plots
    - Partitioning plots
    - Graphics devices
    - Interactive graphics
2. [`{ggplot2}`](./src/d3.ggplot2-essentials.R)

### [E1: Exercises](./src/e1.exercises.R)

### [E2: Appendix](./src/e2.appendix.R)

### [E3: Tricks](./src/e3.tricks.R)

### [Tasks]

1. [Task 1](./tasks/task2.R)
2. [Task 2](./tasks/task1.R)
