# Project Management SOP
This SOP covers how projects will be managed upon receipt into the BioComputation Core. 

1. Project is received in the Core
* All project requests should be submitted through the [online form](http://www.bioinformagic.io/request/)
2. An Issue will be created in the Projects repository and named following the convention below. This will add the project to the [tracking board](https://github.com/RU-NJMS-BICore/Projects/projects/2) and allow assignment of the project.
3. Once the project is assigned, the assigned operator will add a targeted completion time as a comment in the issue. This is not a firm deadline, but simply a goal to keep things on track.
4. When the project is actively being processed, the project card shall be moved to “In Progress” on the [project board](https://github.com/RU-NJMS-BICore/Projects/projects/2).
5. Upon completion, a pull request shall be generated to add necessary files to the repository. These include:
* All QC information
* Any deliverables
* Code utilized to replicate analysis. This is recommended to be in R markdown or Juptyer file. 

6. The uploading files shall be reviewed by the team and subsequently accepted into the repository. For any sensitive projects, upload of final project details can be withheld in review until publication is accepted.
7. After upload or publication withholding, the project shall be moved to the “Completed” space on the [project board](https://github.com/RU-NJMS-BICore/Projects/projects/2). Projects in “Completed will be marked for marked for billing (if applicable) as a comment, and archived upon billing completion. 


## Project Naming Conventions

All projects shall be named in the following convention upon inception in the BioComputation Core:

{Investigator}_{Type of Project}_{Date Received in yymmdd format}_{Descriptor}

### Example
Lemenze_scRNAseq_191009_TestProject
