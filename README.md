# TransMute
Automation for a pipeline to identify and extract translocation and mutation information from mapped DNA sequence reads.

 This script is likely to only be used for mapping mutations 
 in special cases.
 It calls bwa from the bwa folder in the home directory and
 it calls the biostar59647 program from the jvarkit folder 
 in the home directory as well as additional scripts that come with that program.
 samtools is required and a permanent path must be set for 
 this script to work.
 Those three programs are the known dependencies.

 NOTE: scripts run in shell must be allowed to be read, write and 
 be executable.
 use case: chmod +x scriptfilename

 Created by S. Dean Rider Jr., June 2021 for the Leffak Lab.
 Revised and better annotated to include translocations October 2021.
 Modified to include file arguments and compatibility with Darwin 
 and Ubuntu by S. Dean Rider Jr. and David C. Hitch January 2022.

 Example use: bash TransMuteDCH2 referencefile.fa readsfile.fa
 Example use: bash TransMuteDCH2
      then enter filenames when requested
