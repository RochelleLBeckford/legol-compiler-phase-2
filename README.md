# Legol Compiler - Phase 2

## A simple C program that simulates building and stacking Legol Building Blocks.

- [ ] I am a huge Lego fan so I decided that I want to create a simple compiler based on this. A basic Legol-building-block language and output instructions. A single Legol command will be read from the user and then processes it. Then it will print what it is doing. Lastly the program will end.
- [ ] Phase 2 of this project is a little smarter and understands different types of building commands

## What phase 2 does?

- [ ] This program understands more commands: `BUILD`, `STACK`, and `END`
- [ ] It recognizes different colors and sizes
- [ ] This will now tell what `token type` each word is

## How to Use
- [ ] Run the program
- [ ] Type one of these commands:
  - [ ] `BUILD` `<color>` `<size>` (Example: `BUILD pink large`)
  - [ ] `STACK` `<color>` `<size>` (Example: `STACK mint medium`)
  - [ ] `END` (to stop the program)
- [ ] Then the program will analyze each word you typed

## Example
```
-> Welcome to the Legol Mini Compiler!
-> Enter a Legol command (BUILD <color> <size>) or (STACK <color> <size>) or END:
-> STACK green small
-> STACK tokword
-> white tokcolor
-> small toksize
```

## What You'll Learn: Phase 2
- [ ] This version shows:
  - [ ] How this program categorize words -> called "tokens"
  - [ ] Simple if/else statements checks in C
  - [ ] Basic text analysis
  - [ ] How to organize my code with functions
  - [ ] Basic printing to the screen

## Enjoying it's Growth
- [ ] This program is now starting to act like a real compiler:
  - [ ] It is now understanding different word types (aka tokens)
  - [ ] Gives feedback about your input
  - [ ] Being ready for more commands


- [ ] Encompass:
  - [ ] C Programming Language
- [ ] C → This language is best to use when writing a compiler, it is fast, and close to how computers actually work.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)