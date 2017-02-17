# General options
options(tab.width = 2)

# Load packages at the beginning of my R sessions
.First <- function() {
    suppressPackageStartupMessages(library("DoE.base"))
    suppressPackageStartupMessages(library("FrF2"))
    suppressPackageStartupMessages(library("RMySQL"))
    suppressPackageStartupMessages(library("RSQLite"))
    suppressPackageStartupMessages(library("Hmisc"))
    cat("\nWelcome at", date(), "\n\n")
    message("Session Initialization:")
    cat("This R session is initialized by the script at ~/.Rprofile\n")
    cat("Workspace of the last session is restored from ~/.RData\n")
    cat("Current working directory is", getwd(), "\n\n")
    message("About Packages:")
    cat("Packages actively loaded can be listed by the search() command.\n")
    cat("Packages installed can be listed by the library() command.\n")
    cat("Packages can be loaded to this session by the library('pkg') command.\n")
    cat("And packages can be installed by the install.packages('pkg') command.\n\n")
    message("Getting Helps:")
    cat("Help manuals can be launched by command help.start()\n")
    cat("See also https://www.rdocumentation.org with package manuals.\n")
    cat("Package manual can be obtained by command library(help='pkg')\n")
    cat("Function manual can be obtained by command help('function')\n\n")
    message("Getting Around:")
    cat("Invoke OS command: system('command')\n")
    cat("Run an R script: source('script.R')\n")
    cat("Descriptive Statistics: describe(frame$vector)\n")
    cat("One-Way ANOVA: summary(aov(Y~X))\n")
    cat("Box plot: boxplot(Y~X)\n")
    cat("Read in data from CSV: table <- read.table('data.csv', header=TRUE, sep=',')\n")
    cat("Write out data to CSV: write.table(data, file='data.csv', sep=',')\n\n")
    message("Design of Experiments:")
    cat("Generating Design: Package DoE.base, FrF2, FrF2.catlg128\n")
    cat("Analyze Design: aov, lm\n")
    cat("Optimize Design: Package rsm\n")
    cat("CRAN Task View of Design of Experiments: https://cran.r-project.org/web/views/ExperimentalDesign.html\n\n")
}

.Last <- function() {
    cat("\nGoodbye at ", date(), "\n")
}
