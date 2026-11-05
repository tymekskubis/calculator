# Calculator
A Python 3 calculator used from the Terminal, built step by step in SCCM4910.
## What it will do
Add, subtract, multiply and divide two numbers; display the result.
## How to run it
From Week 3: python3 calculator.py
Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer
The program will loop after the calculation is performed to aid in debugging.

Python 3 is required.
run the script 'run.sh' using the command './run.sh'.
if you lack permission, run 'chmod +x run.sh' and run the command above again

Test Case
input 1: 6
input 2: *
input 3: 7
expected output: 42.0

To stop running the program, press Ctrl+C.
---

# the test dependency
for the quality gate to be passed, all 5 tests must pass; otherwise, fail.

# the SCCM4910 environment activation command
source /opt/python-venv/sccm-4910/bin/activate

# ./check.sh
this command runs the 5 tests. if it doesnt work use the command below and retry
chmod +x check.sh


# the expected five-test result
add 5 and 2 should return 7
divide 6 and 2 should return 3
subtract 6 and 2 should return 4
multiply 6 and 2 should return 12
negative add -6 and -2 should return -8

# how exit status is used.
0 means all tests passed
1 means some tests failed
5 means no tests were collected
other numerical codes point to a setup or tool error 
