# ChrisG_Gen811_final_project
Final project repository for Genomics and Bioinformatics class.

"gen811_workbook.txt" details all notes (organized chroonologically by date) for this project.

"scripts" provides only a chronological list of entire scripts used for this project; notes, revisions, and simpler commands are under the corresponding date in the workbook file.

"Results" directory contains all files needed to remake the final paper tables and figures. 

- "GCF*.out" = 5 BLASTp output files, one for each species database and sorted according to bit score.

- "top_2_hits.tsv" = top 2 BLASTp hits for all databases, sorted according to bit score

- "unique_accessions.txt" = all unqiue accession values from the top 2 BLASTp hits + the outgroup sequence accession numbers and titles.

- "concise_WebCD_domains_results.txt" = top blast hit protein domain annotations.

- "unique_seqs.fasta" = the final FASTA file with abbreviated titles used for MAFFT

- "alrt_out.iqtree" = the ultrafast bootstrap + SH-aLRT Maximum-Lkelihood phylogeny of GCPRs.
