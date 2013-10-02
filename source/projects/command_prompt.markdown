---
layout: page
title: Command Prompt Basics
sidebar: true
---

In this project, students will learn how to use the Windows command line tool.

Learning Goals:

* Understand why the command line is useful
* Learn how to replicate many of the explorer actions without the use of a mouse

<div class="note">
<p>This tutorial is open source. If you notice errors, typos, or have questions/suggestions, please <a href="#">submit them to the project on Github</a>.</p>
</div>

## Overview

Tell the students about the history of the command prompt. Go over why understanding the command prompt is important for programmers.

## Opening the command prompt

Students can get to the command prompt by hitting the windows key and typing "command prompt with ruby and rails." Once they hit enter, they should be brought to the command prompt that has paths for Rails and Ruby set in the environment.

<div class="note">
<p>Make sure students are opening "Command Prompt with Ruby and Rails." Many perplexing errors occur when students open the regular version of the Command Prompt. None of the typical commands will work.</p>
</div>

## The basic commands

Show the class how each of the command prompt commands work. It is often helpful to open up the familiar explorer window by typing `explorer .` and showing students that changes you are making in the command prompt affect what one sees in the explorer window.

`dir` = lists the current files in the current directory

`cd` = "current directory" (displays your current path)

`cd ..` = Moves up one directory

`cd <directory_name>` = moves into the named directory

`mkdir` = creates a new directory

`touch <filename>` = creates a new file

`del <file_name>` = deletes the named file withing the directory

`rd <directory_name> /s` = deletes the named directory and all the files within it

`mv <original_file> <new_location>` = moves a file from one directory to another

`rename <original_file> <new_name>` = changes the name of a file

`cls` = clears the command line so you have a clean window

## Exercises

For practice exercises, refer the students here: http://bit.ly/codenow-command-prompt-exercises
