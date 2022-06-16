## Introduction to BASH
Important command line with Linux:
```bash
#Creation of a directory
mkdir <name_of_your_directory>
#Change directory
cd <name_of_your_directory>
#See the files in a directory
ls -a
#Create a file: usually the sign '>' creates a file, be carefull
#if the file is already existing then you will overwrite it.
echo "A VERY FANCY TITLE - How to raise a Seagul" > name_of_your_file.txt
#To continue to write in this file use '>>':
echo "First get some fishbrotchen at MOBY " >> name_of_your_file.txt
#To see what is in your file:
cat name_of_your_file.txt
#OR
more name_of_your_file.txt
#Change the name of a file
mv name_of_your_file.txt raise_a_seagul_new_name.txt
#Remove a file
rm name_of_your_file.txt
.......
## 1.2. Command line tasks
pwd
ls
cd /home/
ls /home
cd ~
.......
## 1.3. Sequence quality control
cp /gxfs_work1/fs2/work-geomar7/smomw240/share/sequence.fastq ~/.
head sequence.fastq
wc l "^>"
fastqc -h
.......
\```# Bioinformatic courses summary 
