latex-homework-template
=======================

<br/>

A LaTeX template for homework, which is developed based on [GitHub - jdavis/latex-homework-template](https://github.com/jdavis/latex-homework-template).

<br/>

## 1 Features

Here are just a few features of this homework template.

1. Title page.
2. Problem markers.
3. Configurable problem numbers (see the last 3 problems for an example).
4. Some examples of commonly used commands about basic writing, figures, mathematics, algorithms and codes.
5. Citation and References.

<br/>

## 2 Files

- homework.cls: Latex class file of specific basic settings.
- example.tex: An example demo for showing how the template works.
- references.bib: source data of citations and references.
- example.pdf: An example demo for showing how the template works.
- figures: figures which will be used in example.tex
- ReadMe.md and ReadMeImages: this file

**Notice:** 

If you need references, please compile `references.bib` file first before compiling `example.tex` file. Otherwise, remember to comment the codes at the end of `example.tex`.

<br/>

## 3 Screenshots

### 3.1 The Cover Page

Includes course name, due dates and authors, allowing single or multiple authors.

![Cover page](/ReadMeImages/1.jpg)

### 3.2 Homework Problems

Support automatically increasing problem counter and different types of problems. For example, solution, proof and multiple sub-problems.

![Example problems 1](/ReadMeImages/2.jpg)

### 3.3 Basic writing

It also allows to set specific problem id. Provided examples for citations, figures, item listing and tables.

![Example problems 2](/ReadMeImages/3.jpg)

### 3.4 Mathematics Problems

Provided examples for writing equations and formulas.

![Example problems 3](/ReadMeImages/4.jpg)

### 3.5 Algorithm Related Problems

Provided examples for algorithms, graph drawing and codes.

![Example problems 4](/ReadMeImages/5.jpg)



## Installing

1. First you will need LaTeX. Instructions on obtaining it can be found here: http://latex-project.org/ftp.html
2. Compiling from the command line will look like the following:

   ```bash
   latexmk example.tex
   ```
3. Or you can use [TeXShop][texshop] or a similar native client to typeset the LaTeX file.

<br/>

## License

This code is distributed under the MIT license. For more info, read the [LICENSE](/LICENSE) file distributed with the source code.

[texshop]: http://pages.uoregon.edu/koch/texshop/
[credit]: http://www.latextemplates.com/template/programming-coding-assignment
