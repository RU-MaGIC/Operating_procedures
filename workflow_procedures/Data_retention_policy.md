# Data Retention Policy

All time frames mentioned below start upon demultiplexing completion.
Any data generated prior to policy effective date and currently retained shall abide as if demultiplexing completed on effective date. For all storage policies, data destruction notifications will be provided at least 2 weeks prior to deletion. Options for longer term storage are outlined below for additional charges. 

## Raw Sequencer Data- Illumina
Raw sequence data is denoted as the .bcl and associated image files. All raw BCL data will be utilized for demultiplexing upon sequencing run completion. This will be performed either via direct upload to Illumina server operations (BaseSpace), or through a local demultiplexing server. Upon completion of the demultiplexing, raw BCL files will be directed to short term archival storage for 90 days and will not be proactively available. After 90 days of storage and confirmation of demultiplexing fideltiy, raw BCL files will be terminated. 

**Time frame justification:** 90 days is sufficient time to capture any potential demultiplexing issues. After such point, the raw files are infrequently (never) utilized, and are not accepted to data repositories. Most service providers refuse any raw sequence data availability as it can reveal cross-investigator multiplexing or operational machine information. 

## Raw Sequencer Data- ONT
Raw sequence data is denoted as .fast5 or squiggle files. All raw data will be utilized for demultiplexing upon sequencing run completion and conversion to FASTQ files. Upon completion of demultiplexing/conversion, raw ONT files will be directed to long term archival storage indefinitely after 90 days. 

**Time frame justification:** 90 days is sufficient time to handle primary analysis. ONT data must be stored indefinitely as the basecalling algorithms are undergoing constant development. Additionally, as the raw data is primary electrical signals, further data is being pulled from this information such as basepair modifications. No ONT raw data should ever be deleted. 

## Demultiplexed Sequencer Data
All demultiplexed data will be proactively provided to end-point users for their personal retention. Data will be retained in short term storage for 3 months, and relegated to long term archival storage for 5 years before final data destruction. Any data pulls from archival data shall incur additional charges to the investigator to accommodate the data accession charges. 
Time frame justification: 3 months in short term storage will allow sufficient time for investigators to appropriately accept the data for their personal retention, as well as ease of dissemination of data to appropriate analysis teams or collaborators. The extended 5 year long term archival storage period will allow for compliant with the NIH storage regulations as well as provide ample time to rescue any potential data destruction. The additional charges for archival data access are to encourage investigators to maintain their own data.

## Analyzed Data
Analyzed data is denoted as the myriad of associated file types generated downstream and is applicable only to data analyzed by the local cores. All analyzed data shall be stored for up to 6 months on local analysis workstations or localized storage. For each analysis, analysis notebook information (including software versions) shall be stored alongside associated script files indefinitely within a code repository as detailed in the raw data management SOP. 

**Time frame justification:** As this data should effectively be reproducible from the .fastq data above, it should not be stored longer than 6 months. At the discretion of the analyzing party, analyzed data may be stored for longer periods to facilitate multi-step experiments or longitudinal studies. Critical is the indefinite storage of notebook information as well as associated scripts in a code repository to allow for reproduction of initial analysis. 


## Longer term storage
For investigators who would prefer extended storage options, there shall be an option for extended storage at appropriate incurred costs. This can be preemptively negotiated at the projects inception or at the point of notification of impending data destruction. 
