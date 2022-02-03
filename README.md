# Autonomous Racing Literature

This repository contains an .csv and a .bib (LaTex Bibtex) file that includes all the literature, research papers and publications in the field of autonomous racing. Although the term of autonomous racing can be referred to different applications (e.g. drone racing) we are focusing in this literature overview only on research from the field of autonomous race cars. This list does not claim to be complete, we are happy to receive feedback from the community about missing papers. This list will be updated a few times a year to include new papers that were recently published.

**Last Update:** 03.02.2022

# Paper Reference
The collected research papers in this repository were used to create the Paper "Autonomous Vehicles on the Edge: A survey on autonomous racing". If you find the information in this repository we would be happy if you can cite the following paper.


# Structure
The excel file currently includes 235 publications. We structured the .csv file mainly into 7 sections that cover both software and hardware developments:

0. Introduction and Overview
1. Perception
   1. Mapping
   2. Localization
   3. Object Detection
2. Planning
   1. Global Planning
   2. Local Planning
   3. Behavioral Planning
   4. Planning & Control
3. Control
   1. Classic Control Approaches
   2. Model Predictive Control
   3. Learning Based Control
   4. Drifting Control
   5. Optimization
4. End-To-End Approaches
   1. Optimization
   2. Deep Learning
   3. Reinforcement Learning
5. Additional Software Development
   1. Evaluation
   2. Complete Software Stack
   3. Modelling
   4. Simulation
6. Autonomous Racing Hardware

# Excel Document
This repository includes an .csv file called "AutonomousRacing_Literature.csv". This file contains all the papers that are related to autonomous vehicle racing. We provided additional columns that give interested readers the possibility to search for specific areas. You can filter and order this file with the following information:
* **Year:** Year the paper was published
* **First Author:** Last name and first name of first author
* **Section:** High-level section we created to structure the papers
* **Subsection:** Subsection in the according high level section to further categorize the papers
* **Topic:** General high-level topic what the paper is covering
* **Method:** Main method/algorithm type that is used in the paper
* **Paper Title:** Official title of the paper
* **Simulation tested:** Was the algorithms (code) developed in the paper tested and evaluated in a simulation environment: yes/no
* **Hardware tested:** Was the algorithms (code) developed in the paper tested on a real autonomous racing vehicle hardware (Small scale, Real Car): yes/no
* **Hardware tested:** To which vehicle type does the hardware belong that was used to test the algorithms (Code) : Small-Scale/Real Car
* **Racing Series:** To which autonomous racing series belongs the paper: Real Car, Roborace, Indy Autonomous vehicle, 1:43, F1TENTH, DonkeyCar, DeepRacer, Auto Rally, Formula Student
* **Link to Paper:** Official link to the website of the paper publisher


# LaTeX bibtex file
This repository includes a .bib (LaTex Bibtex) file called "AutonomousRacing_Literature.bib". This file contains all the papers from the excel file with their corresponding bibtex information (Year, authors, journal type, proceedings, etc.).
Each bibtex entry is named after the "Last Name Author" + "Year".
