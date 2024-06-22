OVERVIEW:

This repository provides a comprehensive guide and associated scripts for performing gene annotation using Whole Genome Sequencing (WGS) data. The process involves retrieving sequencing data, converting it to FastQ format, performing quality checks, trimming poor-quality reads, assembling the sequences de novo, and finally annotating the genes using BLASTX and the PANTHER database. This guide specifically utilizes the sequence data identified by accession number SRR29492069.

Prerequisites
To successfully run the scripts and commands provided in this guide, ensure that your system meets the following prerequisites:

Operating System: Ubuntu (64-bit)
Software: wget, tar, FastQC, Trimmomatic, Velvet, BLASTX
Programming Language: Java (for Trimmomatic)
Internet Access: Required for downloading tools and datasets

Notes
Ensure that all file paths in the commands are correctly set to your working directory.
Regularly check the quality of the sequence data to ensure high accuracy in the final results.
The provided commands assume that you have the necessary permissions to install software and execute scripts on your system.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or issues, please contact Taral Patel at taral2000.patel@gmail.com.
