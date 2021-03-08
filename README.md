# Using REPL.it To Code Along

## Introduction

Setting up and becoming familiar with a programming environment is an early challenge
all programmers face. There are many things to learn - how to navigate a command-line,
run code, manage version control, etc...

There is no way around these things - you will need to learn them soon enough if you want to
start writing your own code. However, there are many online tools available that are helpful
when just starting out. One very helpful tool is [REPL.it](https://repl.it/).

## What is REPL.it?

REPL.it is a website that allows you to create coding environments in the browser on demand,
referred to as REPLs (Read-Evaluate-Print Loops). For example, if you want to practice some
Ruby, you can choose to create a Ruby REPL - a file will be created in the browser for you
where you can write Ruby code. You can run the code you wriet by clicking the **Run** button
at the top of the REPL.

We encourage you to sign up for a REPL.it account (it is free) before continuing. Use it as a
scratch pad - while you are working through the upcoming lessons, open a REPL whenever you want to
practice what you're reading about. For the technical submission at the end of this track, you
will be required to use a REPL.it account to write a bit of your own code.

## Embedded REPLs

To make these early lessons a bit easier to approach, we've included embedded REPLs to write code
in. Most REPLs you'll see will look this:

<iframe height="400px" width="100%" src="https://repl.it/@MaxwellBenton2/yale-2021-repl-intro?lite=true&outputonly=1" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

In these, click **Shell**, then type `irb`and press `Enter`/`Return` on your keyboard. This will
open up Interactive Ruby, allowing you to write and run single lines of Ruby code. If you receive a 
warning about Ruby versions and `irb --legacy`, you can disregard. Once IRB is open, it will accept
Ruby code, including basic math, like `1 + 1`, and return the results of that code when you press `Enter`.

### REPLs with File and Terminal Panels

Later on, you will encounter a REPL that displays two panels - one for writing code, and one for displaying
output, like this one below:

<iframe height="400px" width="100%" src="https://repl.it/@MaxwellBenton2/yale-2021-repl-intro-2?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>

For these, press the **Run** button at the top. The output of any code written in the first panel will be displayed
in the second. In the code snippet, for example, `1 + 1` is already provided. When **Run** is clicked, `2` will be
output in the second panel.

Unlike the first REPL example where you could type anything, if you want to modify the code in this REPL, you'll be prompted
to sign in to your REPL.it account. Editing will automatically create a copy of the REPL under your personal account
so you can modify the original.

For the technical submission, you'll be asked to write code in this type of REPL.

## Conclusion

In the next lesson, we'll practice REPLs and IRB a bit more. The main take away is that there are tools available to you already
that can help you as you learn. You'll eventually set up your own environment to write code in files on your computer. For now,
we have REPL.it to aid us on our journey.

