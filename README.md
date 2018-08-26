# LMFH-VH

Predicting Vrius-host Association with oligonucleotide frequency and Gaussian interaction profile kernels on the heterogeneous network
===========
For the complete viral genome, we have written scripts to extract the "isolate host =" or "host" fields from the annotation files downloaded from complete viral genomes of  NCBI and retrieve the viral genomes from NCBI based on the accession numbers of viruses,thus we can obtain the host information infected by viruses and viral sequences.


Usage codes
---------------
code/dowload_host_of_virus.py  is used to extract the "isolate host =" or "host" fields from the annotation files downloaded from complete viral genomes of  NCBI

code/dowload_virus.py is used to retrieve the viral genomes from NCBI based on the accession numbers of viruses

code/similarity_os.py and code/main.py is used to

 description of datasets
---------------
datasets/dataset I including 71 hosts and 352 viruses which only one specific host genome appeared in the prokaryotic genome database at NCBI[2].

datasets/dataset II including 1075 hosts and 432 viruses which the isolation hosts are all at the species or strain level[2].

datasets/dataset III including 2699 hosts and 820 viruses which is downloaded from RefSeq on 7/25/2015[1].

datasets/onf including onf measures of 352,432 and 820 viruses[2] which are obtained by Jie Ren's tools

Reference and Citation
------------
If you use this datasets and codes , please cite the following paper:

Predicting Vrius-host Association with oligonucleotide frequency and Gaussian interaction profile kernels on the heterogeneous network

Reference in our datasets
------------
[1]Edwards RA, McNair K, Faust K, Raes J, Dutilh BE, Smith M: Computational approaches to predict bacteriophage–host relationships. FEMS Microbiology Reviews 2016, 40(2):258-272.
[2][Ahlgren, Nathan A., Jie Ren, Yang Young Lu, Jed A. Fuhrman, and Fengzhu Sun. "Alignment-free d2* oligonucleotide frequency dissimilarity measure improves prediction of hosts from metagenomically-derived viral sequences." Nucleic Acids Research (2016): gkw1002.](https://academic.oup.com/nar/article/45/1/39/2605663/Alignment-free-d-2-oligonucleotide-frequency)
