# circTools

##Circular RNA 
Circular RNA(circRNA) is a type of RNA molecule that forms a closed-loop structure, whereas traditional RNA molecules (e.g., mRNA, tRNA), have linear structures with distinct start and end points.

Circular RNA is resistant to exonucleases(enzymes that function by removing nucleotides from the ends of RNA or DNA strands) and thus are less susceptible to degradation.

Circular RNA is typically not polyadenylated(the process in which a chain of adenine or poly-A tail, is added to the 3' end of a newly synthesized RNA molecule stabilizing the RNA and helping translation process). 

Circular RNA is highly specific for cell type and developmental stage referring to the fact that circRNA levels may vary during development stages and different cell types may produce different sets of circRNA suggesting circRNA may have unique roles in the function of specific cells or stages of development. 


   -Distinguished by a covalent bond between 3' and 5' ends giving a circular loop structure
   -Can be generated through 'backsplicing' (downstream 5' and upstream 3' splice site are joined) occurring during the splicing of precursor mRNA

   1. Influences gene expression by modulating levels of specific proteins. 

   2. Interacts with proteins influencing stability or activity affecting various cellular processes and signaling pathways 

   3. Regulation of alternative splicing, influencing the production of different mRNA isoforms(proteins that are similar to each other and perform similar roles within cells) 

However, the vast majority of circRNA has an undetermined function. 

##circtools
Current software tools (e.g., DCC, circTest) predict circRNAs from raw sequencing data generating a list of potential circRNA candidates which depending on tissue and condition may contain hundreds to thousands of potential circRNAs. 

circtools is a modular Python3 framework to unify several circRNA tools functionalities in single command line-driven software. 

  Operated through command line interface following circtools subcommand standard. 

##circtools Functionality 
1. RBP Enrichment Screenings
2. circRNA primer design
3. Processing Tools (e.g., FUCHS, DCC)

  
