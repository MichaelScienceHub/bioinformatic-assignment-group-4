# Bioinformatics Assignment - Group 4

## Course
ANA4315: Introduction to Bioinformatics

## Project Description
This project demonstrates a multi-language bioinformatics workflow using Bash automation.

Each group member contributes a script written in a different programming language.  
All scripts print the member's information in a standardized format.

A Bash workflow script runs all scripts and combines their outputs into one CSV file.

## Programming Languages Used
- Python
- R
- JavaScript
- Perl
- Bash

## Workflow Overview
1. Each group member writes a script that prints their information.
2. All scripts are placed inside the scripts/ directory.
3. The Bash script run_workflow.sh runs all scripts automatically.
4. The outputs are collected and combined into a single file output.csv.

## Running the Workflow

Run the workflow using:

bash run_workflow.sh

## Output Artifact

The final output generated is:

artifacts/output.csv

This CSV file contains the combined outputs from all group member scripts.

## Repository Structure

bioinformatic-assignment-group-4
│
├── scripts/
│   ├── michael.py
│   ├── member2.R
│   ├── member3.js
│   ├── member4.pl
│   └── member5.sh
│
├── artifacts/
│   └── output.csv
│
├── run_workflow.sh
│
└── README.md

## Group Members
- Michael (Python)
- Member 2 (R)
- Member 3 (JavaScript)
- Member 4 (Perl)
- Member 5 (Bash)

## Author
Michael – Group Leader
