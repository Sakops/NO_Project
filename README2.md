# JKU Linz NO Project 2

Welcome to JKU Linz NO Project 2!

## Overview

This repository contains the codebase for Project 2 at JKU Linz NO.


### Group Members

| Student ID | First Name | Last Name | E-Mail                   | Workload [%] |
|------------|------------|-----------|--------------------------|--------------|
|    | Ilia | Tavadze |    | [TODO] |
|    | Andreas Helmut | Jelenc |    | [TODO] |
| 08900915 | Wolfram | Laube | wolfram.laube@blauweiss-edv.at | Task 3 [done], Task 4 [50%], Task 5 [90%]  |
| 11806541 | Samuel | Darenskiy | samdarenskiy@gmx.at | [TODO] |
|    | Yasaman | Afsharnaderi | yasaman.afshaar@gmail.com | [TODO] |

## Content

- `main.ipynb`: contains the original problem specification
as given on https://moodle.jku.at/jku/mod/resource/view.php?id=9816287

- `task\<x\>.ipynb`: individual task elaboration as agreed upon on Discord (see table above). The tasks are:
  1. Newton method with Hessian modification 
  2. Linear CG
  3. Non-linear CG: Fletcher-Reevers and Polak-Ribiere methods 
  4. QN methods: BFGS and SR1 methods with line-search. Possible bonus points for SR1 method within the trust-region framework
  5. Derivatives approximation
  6. Outperforming Newton method with a QN

- `master.ipynb`: notebook to build the project IPNB artefact from the individual task notebooks

## Building the project

* Edit `master.ipynb` to include the task notebooks you want to include in the aggregated project notebook.
* Execute the only cell herein. This will generate `project.ipynb`.
* Optionally inspect and adapt the metadata of the generated notebook to modify
author, date, title asf.
* Execute `jupyter nbconvert --to PDF project.ipynb`.
This will generate the `project.pdf` which finally constitutes the submission artefact.

## Submission
The deadline is Sunday, May 19, 23:59

Submission of `project.ipynb` and `project.pdf` (maybe with more distinguished names?)
at https://moodle.jku.at/jku/mod/assign/view.php?id=9816292 
