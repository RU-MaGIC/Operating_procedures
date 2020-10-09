# Data Management SOP
This SOP covers how raw data will be managed. 

1. Sequencing data will be automatically deposited into the Data Temp folder
2. Data will then be immediately demultiplexed. 
3. Demultiplexing will be confirmed with the Genomics Core Facility (or other sequencing provider if applicable)
4. BCL files will be retained in the Data Temp folder for up to 3 months once confirmed. If not changes are made, files we be treated per the data retention policy. 

## FASTQ files
1. All BCL folders will be demultiplexed into individual FASTQ files per sample. 
2. After demultiplexing, the FASTQ files (and ONLY the FASTQ files) will be copied to a project specific directory
3. This directory will be broken down by:
* PI name
* Sub-PI name (if applicable)
* Project following {Investigator}_{Type of Project}_{Date first sequenced or received in yymmdd format}_{Descriptor} naming convention
4. Data will be checked for integrity, and then the preliminary FASTQ files will be deleted from Data Temp. 
5. No BCL files will be stored in this folder. All project folders will include a text file (.txt) with a line for each original BCL folder the samples originated from. 

## Project directory design
Each project directory shall consist of several subdirectories:
- FASTQS: For the raw fastq files
- Analysis: For analyzed files
    - Secondary: For any alignment files (BAM/H5) or standard pipeline outputs
    - Tertiary: For any downstream efforts. This should be broken into specific categories of actions, and a folder for "Deliverables" for each compressed folder of data sent to investigators
- docs: For anything like reports, associated grant proposals, papers etc
- bin: For any associated binary files that are built for this project. If you arent developing any programs, then it should include a file list of software versions
- lib: The location for any specific libraries or packages that are used. This can be replaced with a dockerfile or similar package manager, and can in such cases be combined with bin
- scripts: A directory for random scripts you may have used for this project
- readme.txt: Just a file to describe the structure of the project. 

For ease, an [example structure is provided](https://github.com/RU-MaGIC/Project_template)

## Github/Data repos
All projects are expected to be retained within the lab or collaborators pre-publication. After publication, all project files are expected to be publically available, either through Github or data repositories (such as GEO/ENA/SRA)