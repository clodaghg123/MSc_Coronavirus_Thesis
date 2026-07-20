# Uracil-Favoring Directional Mutational Pressure Across Coronavirus Genera

This project used the CDS sequences of 40 coronavirus genomes across the 4 genera of coronaviruses available on NCBI RefSeq:
* 10 x Alphacoronavirus
* 10 x Betacoronavirus
* 10 x Deltacoronavirus
* 10 x Gammacoronavirus

The CDS sequences investigated:
* The nonstructural proteins (NSP) encoded within ORF1ab: NSP 1-10 & NSP 12-16.
* The structural proteins: spike, envelope, membrane, nucleocapsid.

The command-line code used to extract, align, and run DMP analysis on the CDS sequences is available in "Command_Line".
The list of accession codes and the genus they are categorized into are available in "Accession_Codes" and "mapping.txt", respectively.
The individual and concatenated FASTA files for the CDS aligned with MAFFT G-INS-i are available in "FASTAs_Aligned_G-INS-i".
The output of the directional mutational pressur (DMP) software, currently under development by Lars S. Jermiin, is available in "DMP_output".

