1.  Problems in setwd()

    This creates a set path of directories that are almost certainly not the same on the anyone elses machine and can even change over time on your own machine.

    I assume that RStudio throws an error if the directories do not exist or are not in the same order.

2.  Whats removed when rm(list=ls())

    This deleted user made objects, making it difficult to work on multiple projects at once.

3.  Push Pull and commit

    Push happens remotely

    Pull happens locally

    Commit happens locally

4.  Why do diffs work for source code?

    They work for source code because there usually isn't many many small binary changes like in the writing of a docx file.

5.  Why is markdown useful for Github repos?

    Markdown is useful because it allows for quick text with some markup and you can make a quick website out of it
