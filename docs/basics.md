# The Basics

## R and RStudio

The programming language is called R and is fully open-source. The primary editor used to work in the R programming language is RStudio, which is a free product created by a company called Posit. You can either install R and RStudio on your computer, use Posit Cloud, or access via M3 (one of SMU's supercomputers).

### Install on your computer

To install R and RStudio on your computer, follow the instructions [here](https://posit.co/download/rstudio-desktop/). Be sure to install R first, and then install RStudio. You will never need to open the R installation because RStudio automatically finds your R installation. This option is recommended for those who will primarily be using the same computer and do not need the resources of a high-performance computer.

### Posit Cloud

Posit Cloud works in the browser with a free account. You can make an account and get started [here](https://posit.cloud/). This option is recommended for those who regularly use different computers and do not need the resources of a high-performance computer.

### Using RStudio on M3

In order to use RStudio on M3, you will need to be on a ColdFront allocation, which can be requested on your behalf by a faculty or staff member. For the purposes of this workshop, your instructor will have a ColdFront allocation made available to you. Once you have an active account, you can follow the instructions [here](https://southernmethodistuniversity.github.io/hpc_docs/portal.html) and open an RStudio Server session. This option is recommended for those who need the resources of a high-performance computer for fields such as Machine Learning and Artificial Intelligence.

## Using RStudio

RStudio provides a user-friendly interface to the R programming language. There are 4 main panels that we will go over in the following sections: the file explorer, the console, the script window, and the environment window. Additionally, we will explore how to setup an R project to make using R Studio more convenient.

### File Explorer

In the bottom right panel of RStudio, under the **Files** tab, you can navigate through the files on your computer. From this panel you can import datasets into R, access your R scripts, and set your *working directory*. Your *working directory* is the base folder you want to operate in within an R session. Any filepaths or items saved in your *environment* will use your *working directory* as its base.

To set your *working directory*, navigate to the folder you want to be your *working directory*, click one **More**, and then **Set As Working Directory**. You can always change this, and we will discuss the best way to make use of a *working directory* in the Projects section below.

### Console

In the bottom left panel of RStudio, under the **Console** tab, is where you will execute all of your R code. Each line of code is prompted by the `>` symbol. You do not need to type in the `>`, it is simply to indicate a new line of code. To execute your code you will type out your code and hit the **Enter** key on your keyboard. Below is an example of how to add 2 numbers on the console. The details of this will be explored in future sections.

```{code-block} r
:caption: R Console Input
:name:

> 1 + 1
```

```{code-block} python
:caption: This is a caption
:emphasize-lines: 2,3
:lineno-start: 1

a = 1
b = 2
c = 3
```

```{code-block} r
:caption: Output

[1] 2
```

### Scripts

### Environment

### Projects

## Using R as a Calculator

## Boolean Comparisons

## Assigning Variables

## Get Help