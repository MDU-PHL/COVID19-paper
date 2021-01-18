# COVID19 Genomics 

Data for 
[publications](https://www.medrxiv.org/content/10.1101/2020.05.12.20099929v1)
related genomic epidemiology 
for the Victorian SARS-CoV-2 response from
The Peter Doherty Institute for Infection and Immunity
and the Victorian Department of Health and Human Services
in Australia.

### Reads

Raw genome sequence reads have been deposited at NCBI SRA within 
[PRJNA613958](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA613958).
Every isolate was sequenced with Illumina paired-end 150bp reads.
Some isolates have additional Nanopore data.

The GISAID ID for each set of reads has been added to the BioSample
description.

### Consensus genomes

Early versions of consensus genomes were deposited in 
[GISAID](https://www.gisaid.org/),
but some were rejected due to "frame shifts".
NCBI also rejected them for the same reason.
Investigation is ongoing to confirm if these 
are genuine indels or sequencing artifacts. 

Download a multi-FASTA file
[VIC.ffn](https://github.com/MDU-PHL/COVID19-paper/raw/master/VIC.ffn)
of all genomes.

### Alignment

Download the aligned-FASTA file
[VIC.afa](https://github.com/MDU-PHL/COVID19-paper/raw/master/VIC.afa)

### Tree

Download Newick file 
[VIC.nwk](https://github.com/MDU-PHL/COVID19-paper/raw/master/VIC.nwk)

### Metadata

Download CSV metadata file
[VIC.csv](https://github.com/MDU-PHL/COVID19-paper/raw/master/VIC.csv)

Columns include:
* `VIC_ID` - the identifier used in FASTA, AFA and NWK.
* `NCBI_ID` - this BioSample ID will link to FASTQ and FASTA
* `GISAID_ID` - consensus genome accession
* `Date_coll` - date sample was collected
* `Patient_age` - patient age in years
* `Patient_sex` - patient gender
* `Seq_protocol` - ARTIC V1 or V3
* `Sequencing_technology` - Instrument sequencing was done on
* `PCR_Ct_value` - sample Ct, higher is worse


### Citation

If you use any of the data in this repository or PRJNA613958 please cite:

T Seemann, CR Lane, NL Sherry, S Duchene, AG da Silva, 
L Caly, ML Sait, SA Ballard, K Horan, MB Schultz, 
T Hoang, M Easton, S Dougall,
TP Stinear, J Druce, M Catton, B Sutton, 
A van Diemen, C Alpren, DA Williamson, BP Howden.
<i>Tracking the COVID-19 pandemic in Australia using genomics</i>,
[<b>medR<sub><large>&chi;</large></sub>iv</b>](https://www.medrxiv.org/content/10.1101/2020.05.12.20099929v1),
16 May 2020.
doi:[10.1101/2020.05.12.20099929](https://doi.org/10.1101/2020.05.12.20099929)
