# Python-to-C-compliler

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=306998)
<p><strong>Compiling python to c language using python language, lex and yacc</strong></p>


## Table of Contents
- [Intruduction](#intruduction)
- [Features](#features)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Usage Guide](#usage-guide)

## Intruduction
Lex in compiler design is a program used to generate scanners or lexical analyzers, also called tokenizers. These tokenizers identify the lexical pattern in the input program and convert the input text into the sequence of tokens. It is used with the YACC parser generator. <br/>

YACC (yet another compiler compiler) is a grammar parser and parser generator. That is, it is a program that reads a grammar specification and generates code that is able to organize input tokens in a syntactic tree in accordance with the grammar. <br/>

In this project we are using these concepts and convert python file to c file.


## Features
- Implementation all in python langauge so you don't need other softwares
- Clean code

## Project Structure
The project follows a specific structure to organize its files and directories:
```
diabetes-prediction-app/
├── README.md
├── TokList.txt
├── c.txt
├── lex.py
├── p.txt
├── parser.out
├── parsetab.py
├── yacc.py
```
- `README.md`: Documentation file providing information about the project.
- `TokList.txt`: Tokens are stored in this file after lexical analysis.
- `c.txt`: Output file in c language will be stored here.
- `lex.py`: Script for lexical analysis that read input file and tokenize it.
- `p.txt`: Input python file.
- `parser.out` and `parsetab.py`: Auto generated file after parsing.
- `yac.py`: Script for yacc handling.

## Requirements
To run the x86 assembler, you need to have the following installed on your system:
* Python (version 3.0 or higher)
* PLY package
* Git command line tool (or Git GUI client) to clone the repository.

## Usage Guide
1. Open a terminal and clone this repository: `git clone https://github.com/hoseinmrh/Python-to-C-compliler`
2. Write your python file in `p.txt` then run `yac.py`. Output will be stored in `c.txt`.
