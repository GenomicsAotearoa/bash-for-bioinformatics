# What is a Unix Shell and Bash 

<p style="text-align:left;">
  <b><a class="btn" href="https://genomicsaotearoa.github.io/bash-for-bioinformatics/workshop_material/0_setup_download.html" style="background: var(--bs-green);font-weight:bold">&laquo; Setup </a></b> 
  <span style="float:right;">
    <b><a class="btn" href="https://genomicsaotearoa.github.io/bash-for-bioinformatics/1.UnixShellBasics/" style="background: var(--bs-green);font-weight:bold">3 - Shell Basics and recap &raquo;</a></b>
  </span>
</p>



## Unix Shell

A shell is a computer program that presents a command line interface which allows you to control your computer using commands entered with a keyboard instead of controlling graphical user interfaces (GUIs) with a mouse/keyboard/touchscreen combination.

There are many reasons to learn about the shell:

* Many bioinformatics tools can only be used through a command line interface. Many more have features and parameter options which are not available in the GUI. BLAST is an example. Many of the advanced functions are only accessible to users who know how to use a shell.
* The shell makes your work less boring. In bioinformatics you often need to repeat tasks with a large number of files. With the shell, you can automate those repetitive tasks and leave you free to do more exciting things.
* The shell makes your work less error-prone. When humans do the same thing a hundred different times (or even ten times), they’re likely to make a mistake. Your computer can do the same thing a thousand times with no mistakes.
* The shell makes your work more reproducible. When you carry out your work in the command-line (rather than a GUI), your computer keeps a record of every step that you’ve carried out, which you can use to re-do your work when you need to. It also gives you a way to communicate unambiguously what you’ve done, so that others can inspect or apply your process to new data.
* Many bioinformatic tasks require large amounts of computing power and can’t realistically be run on your own machine. These tasks are best performed using remote computers or cloud computing, which can only be accessed through a shell.

!!! quote "On Unix philosophy"

    “Although that philosophy can’t be written down in a single sentence, as its heart is the idea that the power of a system comes more from the relationships among programs than from the programs themselves. Many UNIX programs do quite trivial things in isolation, but, combined with other programs, become general and useful tools.” ***– Brian Kernighan & Rob Pike***

### Unix vs Linux

Linux is not Unix, but it is a "Unix-like" operating system. Linux system is derived from Unix and it is a continuation of the basis of Unix design. Linux distributions are the most famous and healthiest example of the direct Unix derivatives. BSD (Berkley Software Distribution) is also an example of a Unix derivative.

??? "Unix-like"

    A Unix-like OS (also called as UN*X or *nix) is the one that works in a way similar to Unix systems, however, it is not necessary that they conform to Single UNIX Specification (SUS) or similar POSIX (Portable Operating System Interface) standard.

    SUS is a standard which is required to be met for any OS to qualify for using ‘UNIX’ trademark. This trademark is granted by [‘The Open Group’](https://www.opengroup.org/)

    Few Examples of currently registered UNIX systems include macOS, Solaris, and AIX. If we consider the POSIX system, then Linux can be regarded as Unix-like OS.



## Bash

Bash (Bourne again shell) is a type of Unix Shell and it is the default shell on most modern implementations of Unix and in most packages that provide Unix-like tools for Windows. 

- - - 
<p style="text-align:left;">
  <b><a class="btn" href="https://genomicsaotearoa.github.io/bash-for-bioinformatics/workshop_material/0_setup_download.html" style="background: var(--bs-green);font-weight:bold">&laquo; Setup </a></b> 
  <span style="float:right;">
    <b><a class="btn" href="https://genomicsaotearoa.github.io/bash-for-bioinformatics/1.UnixShellBasics/" style="background: var(--bs-green);font-weight:bold">3 - Shell Basics and recap &raquo;</a></b>
  </span>
</p>

<p align="center"><b><a class="btn" href="https://genomicsaotearoa.github.io/bash-for-bioinformatics/" style="background: var(--bs-dark);font-weight:bold">Back to homepage</a></b></p>