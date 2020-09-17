# Cloud Archive Storage Policy
*Implemented on 9/16/2020*
All sequencing runs shall have an applicable data storage surcharge. This shall be scaled based upon the [average data output per Illumina flow cell](https://support.illumina.com/bulletins/2018/01/approximate-sizes-of-sequencing-run-output-folders.html). All data shall be stored in "hot" storage for 3 months, followed by cold archival storage for 57 months to meet the NIH 5 year data retention policy. 

## Pricing
Pricing is based on [Google Cloud Platform pricing](https://cloud.google.com/products/calculator) with the time frame detailed above. 

Flow cell | Cost for data storage  
--- | --- 
MiSeq flow cell | $10
NextSeq Mid Output | $25 
NextSeq High Output | $75
NovaSeq SP | $75
NovaSeq S1 | $125
NovaSeq S2 | $250
NovaSeq S4 | $750

## Opting out
All investigators have the option to opt out of cloud data storage and not pay the data storage surcharge. This must be declared at project onset during project quotation. If investigators opt for this route, they must sign off accepting data responsibility and the Core will purge all data after 3 months local storage. Data will be transferred to the investigator prior to data deletion, and can be transferred via FTP (investigator must have storage space available), or a physical external hard drive will be purchase (at investigator's expense) with data provided on the hard drive. If the investigator does not make a reasonable attempt to download the data or agree to an external hard drive, the opt out will be void and they will be charged the cloud storage surcharge. 