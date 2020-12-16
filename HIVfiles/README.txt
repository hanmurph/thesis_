This compressed file contains 3 subdirectories and 2 Python scripts.

test_data = The original file containing 12 FASTQ file from a sequencing run.

fastqc_files.py = The first python script, it loops through each of the 12 files and runs QC checks 
on them and then creats two files from each original file (html and zip) These output files are then 
stored in a new directory (fastqc_out)

trimm_script.py = The second python script, loops through each of the FASTQ files from the original
tes_data file and runs the trimmomatic application on them and puts the trimmed FASTQ files in a new 
directory(trimmed_out)

In summary:
test_data = original data
fastqc_files.py = python script runs QC checks
fastqc_out = output from FASTqc
trimm_script.py = python script runs trimming tasks
trimmed_out = output from trimmomatic
