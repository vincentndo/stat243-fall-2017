# Productivity Choices

My field uses proprietary formats (e.g. word documents) for journal submissions.  Any advice on reproducibility there?

I still do not see the advantages of LaTeX over programs like Microsoft Word.  The overhead seems like so much for just the ability to include equations.

# Workflow management

I knew C++ need a make file which links and compiles files to run but writing a make file is hard and the cpp file and h file have many requirements.  Are there better ways to compile a C++ program? 

For python and r, are there any good workflow management tools that we could use? Can we go over make files in more detail? Is there a way to implement them in R?

A little confused about the version control part: If we change the version too frequently, and the version control software just records every version, then what if we do not want to record some of the version? Because when we would like to change something, we have to find the version (to be edited) we want. So how to deal with this issue?

How do I test functions that I write without running the whole thing on the actual data? Sometimes I simulate data or only use the first n=10 lines of the data, but what are some ways I can foresee how my code might break when I run it on the whole data without running it on the whole data?

# Data Management

My previous research involved fluorescent microscopy and flow imaging so we used Box/Dropbox/Google Drive to store our image data (~1GB per image) and subsequent analysis. Are there better ways to store and share files like these? 
A: datproject, dataversion control

Is there a way to avoid data dropping during merge? They point out a situation that many observations data were dropped in a merge, and after they included the dropped observations, the results change. However, it seems they did not mention a solution to avoid data dropping through merge.

Does every dataset need to be normalized? It seems normalizing data takes time and energy. Gentzkow and Shapiro mention some well-trained people can organize data into relational database. When do we need to normalize our data? 

# To what extent?

To what extend should the transparency and observability of research be? If the research  is too transparent, would it harm the legal rights of the author?

I've found that over the course of a data analysis project(s), new goals/tasks
often arise, and the idea of what is "redundant" can change. For instance, when
I find myself performing the same task in two or three different projects I may
want to abstract this task. Or, I may have abstracted some task for different
projects and then find there are differences that ultimately make the
code less clear. Do people have any thoughts on how/when they use abstraction
across different projects and how they plan/organize this?

Under the constraint of time and human resources (e.g. a small team of an advisor and 2 graduate students vs a large team of software engineers that these items seem to be geared toward), many of these practices seem infeasible.  Are there any tools for helping smaller groups achieve good documentation while maintaining sanity?

Isn't there a trade-off between efficiency, generalizability, and readability?

# Workflow documentation

So far, most of the shared analysis code that I've seen consisted of highly polished scripts, or jupyter notebooks, or rmarkdowns etc.  These are useful for being able to reproduce their pipeline; it allows you you go from raw data to figures.  However, it's still hard for me to get a sense of the development process of the scripts and of the exploration that took place prior to deciding on the final analyses.  So as a reader, we still are faced with a highly polished story of the results, rather than a detailed account of the experiment and analyses.

What is a good balance between explicit documentation and self-documenting code?

# Technical

What does refactor code mean in the context of providing explanation to original code?

What is assertion? How it works? Is it only a statement that to compare with the outcome of the program? If the outcome is the same as the statement, does it mean the program is correct?

Pairwise programming seems like it would be slower than just having two people thinking about the problem independently and then comparing their work.

When should we switch from high-level to low-level code?

# Style

Page 35 said "individual functions should not normally be more than 80 or so lines long". Why a function has to be short like this?

What is the purpose of multi-file code? Wouldn't it be better to have one well-documented file?

If I only plan on running an analysis once, is there really a reason to generalize/modularize the code?
