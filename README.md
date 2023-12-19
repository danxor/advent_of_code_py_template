# Advent of Code Python Template

This is yet another Advent of Code template for Python. It contains the files that I suspect I might need in order to download inputs and generate a daily template.

## Struture

I rely heavily on the main script: runner.py; which does all of the heavylifting for me. It downloads the puzzle inputs it solves the test examples as given by the daily instructions and validates that they give the correct answer.

The src-folder contains a class for each day that is used to implement the solutions.

The common-folder contains code to generate a python-file for each day and also the code for downloading the puzzle-inputs.

The data-folder contains all the puzzle-inputs.

## Usage

$ pip3 install -r requirements.txt\
Requirement already satisfied: requests>=2.31.0 ...\
...

$ ./runner.py --test 1\
Day #1 - Part #1: XXX - Ok\
Day #1 - Part #2: XXX - Ok

$ ./runner.py 1\
Day #1 - Part #1: XXX\
Day #1 - Part #2: XXX
