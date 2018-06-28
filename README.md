# Running JavaScript Programs

Note: This document is a work in progress. If you find yourself here and have suggestions for how to improve it or questions contact me on twitter [@dwesty17](https://twitter.com/dwesty17) or by email at j.dylan.westerhold@gmail.com. I'll do my best to get back to you.

Reading Time: **? minutes**

## Lessons
1. [Using a Command Line Interface](https://github.com/project-catalyst/using-a-cli) (? minutes)
1. [Installing Homebrew](https://github.com/project-catalyst/installing-homebrew) (? minutes)
1. **Running a JavaScript Program**
1. [Using Git and GitHub](https://github.com/project-catalyst/using-git-and-github) (? minutes)
1. [Intro to JavaScript](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 1: Variables and Data Types](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 2: Functions](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 3: Conditional Statements and Loops](https://github.com/project-catalyst/overview) (? minutes)
1. [Intro to React](https://github.com/project-catalyst/overview) (? minutes)

## Computer Programming

Computers have the ability to execute operations on numbers much more quickly than humans, however they aren't able to deal with ambiguity in the same way humans can. Thus, they need to be told very specifically what to do.

Programming languages are a series of commands or steps written in a way that can be understood by computer software or hardware. They provide people with a way to instruct computers to execute specific tasks. A helpful and common analogy is that programs are like recipes written in a very specific way in order to get a computer to do what you want it to do.

There is a wide variety of programming languages. Many of them basically do the same general thing, and have the same core concepts. Come were created for specific types of tasks, whereas others grew over the course of their life to be used for something other than what they were originally intended.

## JavaScript

### History

JavaScript is a multipurpose programming language initially created for frontend web development. It's the only programming language gauranteed to be understood by any web browser. It was originally created to standardize web development.

### Node and Present Day

In 2006 (?) Ryan Dahl created a software called Node.js (commonly called Node), which is described as as a JavaScript runtime - or a software that is able to interpret and execute JavaScript programs. Node can be run on most types of computers and in enviornments other than the web browser. One major implication of Node is that you can run a javascript program from the command line, by using the `node` CLI.

If you've already done the lesson on [installing and using Homebrew](https://github.com/project-catalyst/installing-homebrew) then you should already have the Node CLI installed, otherwise take a few minutes to install Homebrew and then install Node with the command `brew install node`.

Once you have node installed we're going to use it to run a very basic JavaScript program, which is also in this project. The project we're going to run is the canonical first program in any languge. If run correctly it will print "Hello, world" in your terminal window.

As an aside, I know it can be frustrating for people who want to learn programming to just follow a set of steps to run a program they didn't create. However, the point of the "Hello, world" program is not that you've achieved any real understanding of a language, but rather that you've installed all the necassary software, done any set up required, and successfully run a program in that language. While, this can be tediuous, it's also something every developer has to do many times throughout their career. When you've completed this exercise take a minute to feel good about all the work you successfully did to run this program, mess around and see if you can get it to do something else, and understand that the majority of what follows this will be writing JavaScript.

## Running your First Program

1. Install node with Homebrew using `brew install node`.
1. Download the zip file for this project, unzip it, and place it in whatever directory you'd like.
1. In your terminal application move into the directory for this project. If on a Mac and this project is on your desktop you can use `cd ~/Desktop/running-js-programs`. (If you haven't yet you probably want to check out the lesson on [using a CLI](https://github.com/project-catalyst/using-a-cli)).
1. Type the command `node hello-world.js` and press enter.

If everything was done correctly you should've seen the program execute successfully and print "Hello, world" in your terminal.

## What Just Happened

The argument after `node` is the path to the file you want to execute. So, because the file was located in the same directory you just need to provide the name of the file. However, we also could have run the command `node running-js-programs/hello-world.js` from the directory that contains this project.

The program in question is a 1 line JavaScript program that uses the `console.log` function, which is built into the JavaScript lanaguage. It simply prints the argument you provide. In this case we provided the string of text 'Hello, world', however we could have passed any string as an arugment. Go ahead and try to print something else.

## Next Lesson

[Using Git and GitHub](https://github.com/project-catalyst/using-git-and-github)
