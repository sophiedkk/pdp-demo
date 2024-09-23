# PDP Godot Demo

Project setup and assets for three small demos during PDP: Catch the Eierballen, Rolling a Die, and Asteroids.

## Prerequisites:

- Install [git](https://git-scm.com/)
- Install [Godot](https://godotengine.org/) 4.3 or higher

## What is a terminal

To run commands you need to have a terminal. On Mac/Linux this should already be installed (just try to search)
for Terminal in you application launcher. On Windows you can use Command Prompt, Powershell, or Windows terminal
(I don't think this one comes by default). If you install git you can also use Git Bash. The nice thing about that
terminal is that you have access to Unix commands.

## How to download

Either download the .zip file under the <> Code menu or open a terminal and navigate to the desired directory with `cd` and run:

```bash
git clone https://github.com/sophiedkk/pdp-demo.git
```
### I don't have git

If you use Mac/Linux you should already have it installed. Type `git` in the terminal and check if that is the case.
If you use Windows you can install it with:

```bash
winget install Git.Git
```

### I can't find the directory

It should create a folder in the directory in which you ran the command. You can see the current directory in
Windows with `chdir` and on Mac/Linux with `pwd`. Again: to navigate directories you can use the `cd` command.

## Open the project in Godot

Open the godot editor and click `Import`. Navigate to the directory of the project and import it.

## Jump to the latest commit

To download the latest commit in this repo and remove all local changes run:

```bash
git fetch --all
git reset --hard origin/main
```
