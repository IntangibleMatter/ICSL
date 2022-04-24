# ICSL Specification

ICSL files are built around two main concepts: Labels and commands.

*Please note: ICSL is designed to work with [a Greg Lobanov save system](https://wandersong.tumblr.com/post/156621436796/how-savedata-management-works-in-wandersong).*

## Labels

A label is a series of commands. These groups of commands can be as long as you want or need them to be. A label is denoted by starting with a `~`, and then a single word which is used to identify the label.

The first line of a label may look like `~chose-yes` or `~below`

## Commands

A command is a line in a `.ICSL` file. A command begins with a single word and is followed by a series of arguments, separated by spaces.
A simple command might look like `jump chose-yes`. In this command, the command is `jump` and the argument is `chose-yes`. This would cause the cutscene to change to running the label `chose-yes`, where it would start running it from the top.