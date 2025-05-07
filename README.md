# bulk-ChIC-
individual scripts for bulk ChIC analysis

Includes 6 scripts:

1. trimming fastq files
2. mapping fast files
3. filtering mapped reads
4. tagging mapped reads
5. creating count matrix
6. creating bedGraph and bigwig files 

Download this repository in your working directory in fast

How to run them:

- Each script is a job script, meaning the commands included will run in the max-cluster

- You need to edit each script for just the  working path 

- Run each script by typing in the terminal sbatch xxx_job_script.sh
  
- Check your  running jobs by squeue --user=aantona
  
- For each job you will receive emails when they START, END, FAIL 
