# Syllabus, Stat 133

- __Notes__:
    + Tentative calendar (weekly topics), subject to changes depending on 
    the pace of the course.
    + Notes (:file_folder:) involves material discussed in class.
    + Reading (:book:) involves material that expands lecture topics, as well as coding examples that you should practice on your own.
    + Misc (:newspaper:) is supporting material that is worth taking a look at.


-----


## 0. Course Introduction

- :card_index: __Dates__: Aug 22-24
- :paperclip: __Topics__: Welcome to Stat 133. We begin with the usual review of the course policies/logistics, expectations, topics in a nutshell, etc. Then, we move on with an unconventional introduction to _computing with data_ using my favorite analogy "Data Analysis is a lot like Cooking".
- :file_folder: __Notes__:
    + [Welcome to Stat 133](../slides/00-welcome.pdf) (slides)
    + [Data Analysis is a lot like cooking](../slides/01-dac-cooking.pdf) (slides)
- :book: __Reading__:
    + [Course policies](policies.md)
    + [Piazza etiquette](piazza.md)
    + [FAQs](faqs.md)
- :microscope: __Lab__: No lab
- :newspaper: __Misc__:
    + [What is Data Science?](../papers/what-is-data-science.pdf)
- :speaker: __To Do__: 
    + Install [__R__](https://cran.cnr.berkeley.edu/) 
    + Install [RStudio](https://www.rstudio.com/products/rstudio/download/#download) Desktop (open source version, free)


-----


## 1. The Big Picture and R Survival Skills

- :card_index: __Dates__: Aug 27-31
- :paperclip: __Topics__: First things first. At the conceptual level we'll discuss how data analysis projects usually start with a Research Question. Also, we'll describe how Data can actually be seen from a triangular perspective (i.e. my "3 Views of Data"). At the practical level, you'll begin learning basic survival skills for R, followed by an overall review of the RStudio workspace. Then we move on to discuss basic data types and their implementation in R around vectors and other data structures. 
- :file_folder: __Notes__:
    + [The Starting Point: Research Questions](../slides/02-research-question.pdf) (slides)
    + [The Three Views of Data](../slides/03-data-perspectives.pdf) (slides)
    + Be the Boss of your Data (talk and chalk)
    + [Data Types and Vectors](../slides/04-R-vector-types.pdf) (slides)
- :book: __Reading__:
    + [First contact with R](../tutorials/01-intro-to-R.md) (tutorial)
    + [Intro to Rmd files](../tutorials/02-intro-to-Rmd-files.md) (tutorial)
- :microscope: __Lab__:
    + [Getting started with R and RStudio](../labs/lab01-R-basics.md) (due Sep-01)
- :newspaper: __Misc__:
    + [Introduction to R Markdown](http://rmarkdown.rstudio.com/lesson-1.html) (by RStudio)
- :bulb: __Cheat sheet__: 
    + [RStudio cheat sheet](../cheatsheets/rstudio-IDE-cheatsheet.pdf)
    + [R markdown cheat sheet](../cheatsheets/rmarkdown-cheatsheet-2.0.pdf)
- :dart: __WARM-UP 1__:
    + [Markdown practice](../hws/warmup01-markdown.pdf) (due Sep-04, open till Sep-18)


-----


## 2. More Data Structures: Arrays, Lists, and Dataframes

- :card_index: __Dates__: Sep 03-07 _(Holiday Sep-03)_
- :paperclip: __Topics__: In this week you'll keep learning more about R data structures like arrays and lists. More specifically, we'll focus on fundamental concepts like atomicity, vectorization, recycling, and subsetting. And given that we are studying vectors and its cousins, we'll briefly review the traditional _base_ graphics approach that is based on R vectors.
- :file_folder: __Notes__:
    + [Arrays and Factors](../slides/05-arrays-factors.pdf) (slides)
    + [Lists](../slides/06-lists.pdf) (slides)
    + [Data Frames](../slides/07-data-frames.pdf) (slides)
    + [Base Graphics I](../slides/08a-base-graphics1.pdf) (slides)
    + [Base Graphics II](../slides/08b-base-graphics2.pdf) (slides)
- :book: __Reading__:
    + [Intro to vectors](../tutorials/03-intro-to-vectors.md) (tutorial)
- :microscope: __Lab__:
    + [Getting started with vectors and factors](../labs/lab02-vector-basics.md) (due Sep-08)
- :newspaper: __Misc__:
    + [chapter 20: Vectors](http://r4ds.had.co.nz/vectors.html) (_R for Data Science_ by Grolemund and Wickham)
- :bulb: __Cheat sheet__: 
    + [Base R](../cheatsheets/base-r-cheatsheet.pdf)
- :dart: __WARM-UP 2__:
    + [Vectors and Factors](../hws/warmup02-vector-basics.pdf) (due Sep-11, open till Sep-18)


-----


## 3. Housekeeping: Filesystem and Bash Commands

- :card_index: __Dates__: Sep 10-14
- :paperclip: __Topics__: Data Analysis Projects (DAPs) are made of files and directories. Therefore, we need to review some fundamental concepts such as the file-system, the command line interface, and some basic shell commands. At the practical level, you will have the chance to practice some data manipulation operations on data frames.
- :file_folder: __Notes__:
    + [Filesystem Basics](../slides/09-filesystem-basics.pdf) (slides)
    + [Shell Basics](../slides/10-shell-basics.pdf) (slides)
    + [Working with files](../slides/11-working-with-files.pdf) (slides)
- :book: __Reading__:
    + [Linux Tutorial](https://ryanstutorials.net/linuxtutorial/) lessons 1-5 (by Ryan Chadwick)
    + [The Unix Shell](http://swcarpentry.github.io/shell-novice/) lessons 1-3 (by Software Carpentry)
- :microscope: __Lab__:
    + [Command Line Basics](../labs/lab03-command-line-basics.md) (due Sep-15)
- :newspaper: __Misc__:
    + [Linux Command Line tutorial](https://www.guru99.com/terminal-file-manager.html) (by Guru99)
- :bulb: __Cheat sheet__:
    + [command line cheat sheet](../cheatsheets/command-line-cheatsheet.pdf)
- :dart: __WARM-UP 3__:
    + [Data Frame Basics](../hws/warmup03-data-basics.pdf) (due Sep-18)


-----


## 4. Housekeeping: Version Control with Git and GitHub

- :card_index: __Dates__: Sep 17-21
- :paperclip: __Topics__: We continue talking about filestructure topics, and we introduce basic notions of version control systems (VCS) using Git, and the companion hosting platform GitHub.
On the Data side, we begin our discussion about Tables: the most common form in which data is stored, handled, and manipulated. Consequently, we need to talk about the typical storage formats of tabular data, and the relationship between tables and R data frames.
- :file_folder: __Notes__:
    + [Git Basics](../slides/12-git-basics1.pdf) (slides)
    + [Git Workflow](../slides/13-git-basics2.pdf) (slides)
    + [Data Tables](../slides/14-data-tables.pdf) (slides)
    + [Importing Tables in R](../slides/15-importing-tables.pdf) (slides)
- :book: __Reading__:
    + Read sections 4 to 9 in Part I [Installation](http://happygitwithr.com/installation-pain.html) (_Happy Git and GitHub for the useR_ by Jenny Bryan et al.)
    + [Basic manipulation of Data Frames](../slides/14-data-frame-basics.pdf) (slides)
- :microscope: __Lab__:
    + [Git Basics](../labs/lab04-git-basics.md) (due Sep-22)
    + [Get your Github Classroom repo](../labs/lab04-github-classroom.pdf)
- :newspaper: __Misc__:
    + [Data Import](http://r4ds.had.co.nz/data-import.html) (_R for Data Science_ by Grolemund and Wickham)
    + [Organizing data in spreadsheets](http://kbroman.org/dataorg/) (by Karl Broman)
- :bulb: __Cheat sheet__:
    + [Data import cheat sheet](../cheatsheets/data-import-cheatsheet.pdf)
    + [git cheat sheet](../cheatsheets/git-cheatsheet.pdf)
- :dart: __WARM-UP 4__:
    + [Data Frame Basics](../hws/warmup04-exploring-nba.pdf) (due Sep-25)


-----


## 5. Transforming and Visualizing Tabular Data

- :card_index: __Dates__: Sep 24-28
- :paperclip: __Topics__: Because data tables are so ubiquitous, it's important that you learn how to manipulate them via R data frames in a more modern and syntactic way. How? By following the _data plying_ framework provided by the package `"dplyr"`. Likewise, we begin a comprehensive discussion on concepts for data visualization.
- :file_folder: __Notes__:
    + [Datavis: Introduction](../slides/17-data-vis1.pdf) (slides)
    + [Datavis: Encoding Data in Graphs](../slides/18-data-vis2.pdf) (slides)
    + [Datavis: The Visual System](../slides/19-data-vis3.pdf) (slides)
- :book: __Reading__:
    + ["dplyr" tutorial slides](../slides/16-dplyr-tutorial.pdf) (by Hadley Wickham)
    + ["ggplot2" lecture](../slides/22-ggplot-lecture.pdf) (by Karthik Ram)
- :microscope: __Lab__:
    + [Getting started with dplyr and ggplot2](../labs/lab05-dplyr-ggplot-basics.md) (due Sep-29)
- :newspaper: __Misc__:
    + [tibbles vignette](https://cran.r-project.org/web/packages/tibble/vignettes/tibble.html)
    + [Introduction to dplyr](https://cran.r-project.org/web/packages/dplyr/vignettes/dplyr.html) (by Hadley Wickham)
- :bulb: __Cheat sheet__:
    + [Data transformation cheat sheet](../cheatsheets/data-transformation-cheatsheet.pdf)
    + [Data visualization with ggplot2](../cheatsheets/ggplot2-cheatsheet-2.1.pdf)
- :dart: __WORK-OUT 1__:
    + [Data Wrangling and Visualization](../hws/workout1-instructions.pdf) (due Oct-05)


-----


## 6. More Visualization

- :card_index: __Dates__: Oct 01-05
- :paperclip: __Topics__: We continue reviewing more concepts of data visualization. 
- :file_folder: __Notes__:
    + [Datavis: Using Color](../slides/20-data-vis4.pdf) (slides)
    + [Datavis: Effective Charts](../slides/21-data-vis5.pdf) (slides)
- :book: __Reading__:
    + ["ggplot2" lecture](../slides/22-ggplot-lecture.pdf) (by Karthik Ram)
- :microscope: __Lab__:
    + [More data wrangling, and exporting outputs](../labs/lab06-more-data-wrangling.md) (due Oct-06)
- :newspaper: __Misc__:
    + [Tidy Data](../papers/tidy-data-wickham) (by Hadley Wickham)
- :bulb: __Cheat sheet__:
    + [Data transformation cheat sheet](../cheatsheets/data-transformation-cheatsheet.pdf)
- :mortar_board: __MIDTERM 1__: Friday Oct-05



-----


## 7. Transition to Programming Basics for Data Analysis (part 1)

- :card_index: __Dates__: Oct 08-12
- :paperclip: __Topics__: You don’t need to be an expert programmer to be a data scientist, but learning more about programming allows you to automate common tasks, and solve new problems with greater ease. We'll discuss how to write basic functions, the notion of R expressions, and an introduction to conditionals. 
- :file_folder: __Notes__:
    + [Creating functions](../tutorials/06-creating-functions.md) (tutorial)
    + [Introduction to functions](../tutorials/07-intro-to-functions.md) (tutorial)
    + [Introduction to R expressions and conditionals](../tutorials/08-intro-to-expressions-conditionals.md) (tutorial)
- :microscope: __Lab__:
    + [Getting started with functions and conditionals](../labs/lab07-simple-functions.md) (due Oct-13)
- :newspaper: __Misc__: 
    + [chapter 19: Functions](http://r4ds.had.co.nz/functions.html) (_R for Data Science_ by Grolemund and Wickham)
- :dart: __WARM-UP 5__:
    + [Function Basics](../hws/warmup05-functions.pdf) (due Oct-16)


-----


## 8. Programming Basics for Data Analysis (part 2)

- :card_index: __Dates__: Oct 15-19
- :paperclip: __Topics__: In addition to writing functions to reduce duplication in your code, you also need to learn about iteration, which helps you when you need to do the same operation several times. Namely, we review control flow structures such as `for` loops, `while` loops, `repeat` loops, and the `apply` family functions.
- :file_folder: __Notes__:
    + [Introduction to loops](../tutorials/09-intro-to-loops.md) (tutorial)
    + [More about functions](../tutorials/10-more-functions.md) (tutorial)
    + [Functions](http://adv-r.had.co.nz/Functions.html) (_Advanced R_ by H. Wickham)
    + [Environments](http://adv-r.had.co.nz/Environments.html) (_Advanced R_ by H. Wickham)
- :microscope: __Lab__: 
    + [Getting started with loops](../labs/lab08-simple-loops.md) (due Oct-20)
- :newspaper: __Misc__:
    + [chapter 21: Iteration](http://r4ds.had.co.nz/iteration.html) (_R for Data Science_ by Grolemund and Wickham)
- :dart: __WARM-UP 6__:
    + [Pipelines and Programming Basics](../hws/warmup06-loops.pdf) (due Oct-23)


-----


## 9. Manipulating Character Strings and Testing Functions

- :card_index: __Dates__: Oct 22-26
- :paperclip: __Topics__: At its heart, computing involves working with numbers. However, a considerable amount of information and data is in the form of text. Therefore, you also need to learn about character strings, and how to perform basic manipulation of strings. In parallel, we'll keep working on writing functions, especially focusing on testing functions.
- :file_folder: __Notes__:
    + [Intro to testing functions](../tutorials/11-testing-functions.md) (tutorial)
    + [Character strings in R](http://www.gastonsanchez.com/r4strings/chars.html) (_r4strings_ by Sanchez)
    + [Basic string manipulations](http://www.gastonsanchez.com/r4strings/manip.html) (_r4strings_ by Sanchez)
- :book: __Reading__:
    + [testthat: Get started with testing](../papers/testthat-wickham.pdf) (by Wickham)
- :microscope: __Lab__: 
    + [Getting started with strings](../labs/lab09-tests-strings-basics.md) (due Oct-27)
- :newspaper: __Misc__:
    + [chapter 14: Strings](http://r4ds.had.co.nz/strings.html) (_R for Data Science_ by Grolemund and Wickham)
- :bulb: __Cheat sheet__:
    + [Stringr cheat sheet](../cheatsheets/stringr-cheatsheet.pdf)
- :dart: __WORK-OUT 2__:
    + [Functions, tests, and strings](../hws/workout02-instructions.pdf) (due Nov-05)


-----


## 10. Regular Expressions

- :card_index: __Dates__: Oct 29 - Nov 01
- :paperclip:  __Topics__: To unleash the power of strings manipulation, we need to take things to the next level and learn about Regular Expressions. Namely, Regular expressions are a tool that allows us to describe a certain amount of text called "patterns". We'll describe the basic concepts of regex and the common operations to match text patterns.
- :file_folder: __Notes__:
    + [Regexpal](http://regexpal.com.s3-website-us-east-1.amazonaws.com/) tester tool.
    + [Long Jump World Record example](../tutorials/12-strings-example.md)
    + [Log file example](../tutorials/13-more-regex.md)
- :book: __Reading__:
    + [Handling Strings in R](http://www.gastonsanchez.com/r4strings) (by Sanchez)
- :microscope: __Lab__:
    + [Regular Expressions](../labs/lab10-regex-basics.md) (due Nov-02)
- :bulb: __Cheat sheet__:
    + [Regular Expressions cheat sheet](../cheatsheets/regular-expressions-cheatsheet.pdf)
- :dart: __WORK-OUT 2__:
    + _Keep working on your workout02 assignment._


-----


## 11. Random Numbers, Simulations, and Shiny Apps

- :card_index: __Dates__: Nov 05-09
- :paperclip: __Topics__: Random numbers have many applications in science and computer programming, especially when there are significant uncertainties in a phenomenon of interest. In this part of the course we'll look at some basic problems involving working with random numbers and creating simulations. Jointly, we will briefly discuss Shiny apps to better visualize the results of some simulations. This type of apps are a nice companion to R, making it quick and simple to deliver interactive analysis and graphics on any web browser.
- :file_folder: __Notes__:
    + [Introduction to random numbers](../tutorials/14-intro-to-random-numbers.md)
    + [Coin toss shiny app](../apps/coin-toss)
    + [shiny tutorial](../23-slides/shiny-tutorial.pdf) (by Grolemund)
- :book: __Reading__:
    + [Part 1 - How to build a Shiny app](https://vimeo.com/rstudioinc/review/131218530/212d8a5a7a/#t=0m0s) (video)
- :microscope: __Lab__:
    + [Random numbers and simulations](../labs/lab11-random-simulations.md) (due Nov-10)
- :newspaper: __Misc__:
    + [Part 2 - How to customize reactions](https://vimeo.com/rstudioinc/review/131218530/212d8a5a7a/#t=42m2s) (video)
    + [Part 3 - How to customize appearance](https://vimeo.com/rstudioinc/review/131218530/212d8a5a7a/#t=1h32m41s) (video)
- :bulb: __Cheat sheet__:
    + [shiny cheat sheet](../cheatsheets/shiny-cheatsheet.pdf)
- :dart: __WARM-UP 7__:
    + [Strings and Regular Expressions](../hws/warmup07-strings.pdf) (due Nov-13)


-----


## 12. R packaging (part 1)

- :card_index: __Dates__: Nov 12-16 _(Holiday Nov-12)_
- :paperclip: __Topics__: Packages are the fundamental units of reproducible R code. They include reusable functions, the documentation that describes how to use them, and sample data. In this part we'll start describing how to turn your code into an R package.
- :file_folder: __Notes__:
    + [Programming S3 Classes](http://www.gastonsanchez.com/packyourcode/coin.html)
    + [Methods](http://www.gastonsanchez.com/packyourcode/methods1.html) (by Sanchez)
- :book: __Reading__:
    + [Package Structure](http://r-pkgs.had.co.nz/package.html) (R packages by Wickham)
    + See package components: [http://r-pkgs.had.co.nz/](http://r-pkgs.had.co.nz/) (R packages by Wickham)
- :microscope: __Lab__:
    + [HTML and Web scraping](../labs/lab12-web-scraping.md) (due Nov-17)
- :bulb: __Cheat sheet__:
    + [Package Development cheat sheet](../cheatsheets/packages-cheatsheet.pdf)
- :dart: __WORK-OUT 3__: 
    + [R package](../hws/workout03-package-roller.pdf) due Dec-02


-----


## 13. Thanksgiving Week

- :card_index: __Dates__: Nov 19-23 _(Holiday Nov 21-23)_
- :paperclip: __Topics__: More about creating an R package
- :file_folder: __Notes__:
    + Discussion on the R packaging process (chalk and talk).


-----


## 14. R Packaging (part 2)

- :card_index: __Dates__: Nov 26-30
- :paperclip: __Topics__: Creating an R package can seem overwhelming at first. So we'll keep working on the creation of a relatively basic package. This will give you the opportunity to apply most of the concepts seen in the course.
- :file_folder: __Notes__:
    + [Pack YouR Code](http://www.gastonsanchez.com/packyourcode) (by Sanchez)
- :book: __Reading__:
    + See package components: [http://r-pkgs.had.co.nz](http://r-pkgs.had.co.nz/) (R packages by Wickham)
- :microscope: __Lab__:
    + Take advantage of lab discussion to work on the workout03 assignment
- :bulb: __Cheat sheet__:
    + [Package Development cheat sheet](../cheatsheets/packages-cheatsheet.pdf)


-----


## 15. RRR Week and Final Exam

- :card_index: __Dates__: Dec 03-07
- :paperclip: __Topics__: Prepare for final examination
- :file_folder: __Notes__:
    + No lecture. Instructor will hold OH (in 309 Evans)
- :mortar_board: __FINAL__: Mon Dec-10, 7-10pm (Dwinelle 155 and Hearst Gym 228)
    + See announcement about the final test on bCourses


-----
