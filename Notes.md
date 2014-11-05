# Week 1

## Series Motivation
- The question should come first, and then the data. Can you answer the question you are interested in solving with the data you have available?
- Caffo - brain imaging
- Leek - genomic data
- Peng - fine particulate matter
- Why Data Science? There is a ton of data that is easier to collect and store than it ever has been. There is even money out there available as prizes to folks who solve data science puzzles.
-We will be using R because there are so many packages for all the processes in data science and a nice IDE. Ipong could be used.
-Data Science intersects 3 skills, Math & Statistics Knowledge, Hacking Skills, and Substantive Expertise
Hacking Skills are needed partly because you can code and partly because you need to do your own seraches to find out stuff. This isn't all collected together and crystalized for you yet.

## The Data Scientist's Toolbox
- Tasks of a Data Scientist
  - Define the question
  - Define the ideal data set
  - Determine what data you can access
  - Obtain the data
  - Clean the data
  - Exploratory data analysis
  - Statistical prediction/modeling
  - Interpret results
  - Challenge results
  - Synthesize/write up results
  - Create reporducible code
  - Distribute results to other people
- Tools
  - Main tool is R and its IDE, RStudio
  - R Markdown - Document  (.Rmd)
  - Git for version control and GitHub for distribution

## Getting Help
- Post questions to message boards and up-vote or respond to questions.
- Try to answer your own questions using other online resources
  - Google
  - R documentation
    - ?rnorm
    - help.search("rnorm")
    - args("rnorm")
    - rnorm # shows the code itself, which turns out to be a call to a C function
    - http://cran.r-project.org/doc/contrib/Short-refcard.pdf
- Post your answers when you have found them for yourself, for the sake of your classmates
- How to ask an R question
  - What steps will reporduce the problem?
  - What is the expected output
  - What do you see instead?
  - What verison of the product are you using?
  - What OS and version do you have?
- How to ask a data analysis question
  - What is the question you are trying to answer?
  - What setsp/tools did you use to answer it?
  - What id you expect to see?
  - What do you see instead?
  - What other solutions have you thought about? (Avoid them responding with low hanging fruit)
- Good Titles for questions
  - R 2.15.0 lm() function on Mac OSX 10.6.3 -- seg fault on large data frame
  - Using principal components to discover common variation in rows of a matrix, shoud I use U, D, or V^T
- Good Etiquette
  - Describe the goal
  - Be explicit
  - Be brief
  - Be polite
  - Follow-up when you find an answer
- Bad Etiquette
  - Ask other people to do your homework
  - Post homework questions on mailing lists or forums
  - Email multiple lists at the same time or send to the wrong lists
  - Ask General data analysis questions on R forums

## Finding Answers
- Characteristics of a Data Hacker
  - Be willing to find your own answers
  - Learn where to look for them
  - Be willing to learn new packages and new data types
  - Be willing to admit ignorance
  - Be polite but relentless
- Where to look for different questions
  - R programming
    - Class forum archives
    - RTFM
    - Read the Web
    - Ask a skilled friend
    - Post to class forums
    - Post ot R mailing list or Stackoverflow
  - Data Analysis/Statistics
    - Same, but post to CrossValidated
- How to Google Data Science Questions
  - Stackoverflow, use the tag "[r]"
  - Google [data type] data analysis, [data type] R package
    - biostatistics - medical data
    - Data Science - web analytics
    - Machine Learning (machine learning)
    - Natural Language processing (text processing)
    - Signal processing (data from electrical signals)
    - Business analytics (data on customers)
    - Econometrics (economic data)
    - Statistical process controll (data about industrial processes)

## Courses in Data Science Track
### R Programming Overview
- Data types
- Subsetting
- Reading and writing data
- Control structures
- Fonctions
- Scoping
- Vectorized operations
- Dates and times
- Debugging
- Simulation
- Optimization

- readLine
- lapply

### Getting Data Overview
- Raw vs. tidy data
  - Original source
  - often hard to use for data analyses
  - data analysis inclues processing
  - raw data may only need to be processed once
  - Processed data is ready for analysis
  - processing can include merging, subsetting, transforming, etc
  - All steps should be recorded
- Downloading files
- Reading data (Excel, XML, JSON, MySQL, HDF5, Web)
  - dbConnect()
  - merge()
- Merging data
- Reshaping data
- Summerizing data
- Finding and replacing
- Data resources

### Exploratory Data Analysis Overview
- Principles of analytic graphics
  1. Show comparisons
  2. Show causality, mechanism, explanaton
  3. Show multivariate data
  4. Integrate multiple modes of evidence
  5. Describe and document the evidence
  6. Content is king
- exploratory graphs
- plotting systems in R
  - base
  - lattice
  - ggplot2
- Hierarchical clusting, k-means clustering, dimensional reduction

### Reproducible Research Overview
- Structure of Data Analysis
  - Define the question
  - Define the ideal data set
  - Determine what data you can access
  - Obtain the data
  - clean the data
  - Exploratory data analysis
  - Statistical prediction/modeling
  - Interpret results
  - Challenge results
  - Synthesize/write up results
  - Create reproducible code
- Organizing a Data Analysis
  - Data, Raw and Processed
  - Figures, Exploratory and Final
  - R Code, Raw scripts and Final Scripts and Markdown files
  - Text - Readme and Analysis files
- Markdown
- LaTeX
- R Markdown
- Evidence-based data analysis
- RPubs

### Statistical Inference Overview
- Basic probability
- Likelihood
- Common distributions
- Asymptotics
- Confidence intervals
- Hypothesis tests
- Power
- Bootstrapping
- Non-parametric tests
- Basic bayesian statistics

### Regression Models Overview
- Linear regression
- Muliple regression
- Confounding
- Residuals and diagnostics
- And so much more...
- Regression to the mean
- More math than some other classes, but they will deny us the Calculus that could make the derivations easy. :(

### Practical Machine Learning Overview
- Machine learning in R
- There are other classes for Machine learning in other languages
- caret
- cross validation
- prediction trees
- forecasing
- Sensitivity and specificity
- Correlated predictors
- boosting

### Building Data Products Overview
- How to build your own R package
- rCharts, Slidify, Shiny

# Week 2
## Command Line Interface

## Introduction to Git

## Introduction to GitHub

## Creating a GitHub Repository

## Basic Git Commands

## Basic Markdown

## Installing R Packages

## Installing Rtools

# Week 3

## Types of Questions

## What is Data?

## What about Big Data?

## Experimental Design
