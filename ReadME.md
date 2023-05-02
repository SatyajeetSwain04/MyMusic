# MarksheetGenerator
A script that can quicky generate Marksheets using CSV inputs

## Introduction
This script was created due to the repetative task of generating Marksheets for the classes/labs I teach.  
I wanted a quicker way to pull information and then generate marksheets from information that was accessible from other sources.

The solution I came up with was this, using CSVs it is possible to describe the Grading scheme (columns) and specify the Students, divided into Sections.

## Using the script
You must create files the describe the marksheets you wish to generate.  

There are three main files you need to have:
* Students
* Grading (Rubric)
* Sections (Partion)

Each file has a slightly different format, but they are all CSVs.

Install the needed libraries by running `pip -r requirements.txt`.

After this, you can edit the flags and constants in the python script.

Finally, run the python script doing something like `py generate.py`.
