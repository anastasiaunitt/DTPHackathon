# DTPHackathon


Looking at gene duplication events in the lineage that leads to humans, focusing on important evolutionary stages such as the evolution primates, mammals and vertebrates.

Used 8 genomic sequences acquired from GenBank - Homo sapiens, Pan troglodytes, Macaca mullatta, Mus musculus, Gallus gallus, Danio rerio, Callorhinchus milii, Branchiostoma floridae. Chosen for as they had good genomes and advantageous positions on the tree.
Downloaded the protein sequences as this is what OrthoFinder uses
Ran Orthofinder on these sequances. It took approximately 12 hours for OthoFinder to run on these sequences.

Quality of the OrthoFinder analysis is good as 96.1% of the total genes were in orthogroup and similar levels of orthogroup assignment

The species tree that OrthoFinder inferred was not correct so we re ran the last step of the process with the correct tree. We provided the correct tree by using the PhyloT online tree builder that uses taxonomic information form NCBI to build a tree. 
