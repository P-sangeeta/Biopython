# Biopython
this repository is created by Sangeeta Parthasarathy

this repository contain python scripts to practice as part of course BVG-7003 at University Laval.

The Biopython Project is an international association of developers of freely available Python (http://www.python.org) tools for computational molecular biology.

The Biopython web site (http://www.biopython.org) provides an online resource for modules, scripts, and web links for developers of Python-based software for bioinformatics use and research
Biopython is a set of libraries, which has content useful for molecular biologist working on the computer. To use Biopython a basic knowledge of programming is a must but overall it make the job of biologist easier in finding the complex genomics answers.
# Installing Biopython
pip install biopython

# if you don’t have pip
apt install python-pip

# to check version of Biopython

python -c "import Bio; print(Bio.__version__)"
# Reading sequence files in Biopython
main advantage of  Biopython is that it  deals with diverse sequence file formats. 
the primary module is BioSeqIO
https://biopython.org/wiki/SeqIO

# Examples
For counting fasta records from NC_000913.faa file count_fasta.py is used. The output is in count.txt.

To print the 4140 ID of  NC_000913.faa file count_record.py is used. The output is in count_record.txt.

To check the number of proteins that do not start with methionine from NC_000913.faa  check_start_met.py was used. The output was 208 records that do not start with Methionine.

Convert.py was used to convert a sequence from .gbk to .fasta file. The out put is in convert.txt

To filter the sequence less than 100 amino acids long filter1.2.py was used and the output was in filter1.2 text

edit.py was used to edit the sequence to take everything except the last letter from  PGSC_DM_v3.4_pep_representative.fasta. and the result is in edit.txt.

To select record of type CDS from NC_000913.gbk and create a file name NC_000913_cds.fasta filter2.py was used. The output was saved in filter2.txt

total_gene_lengths is used to select gene type features and calculate the total length including all the genes from from NC_000913.gbk.


