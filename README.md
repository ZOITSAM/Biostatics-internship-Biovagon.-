# Summer Bioinformatics Internship 2026 - Biovagon 
Day 1- 
I searched in (https://www.ncbi.nlm.nih.gov/gene/) the INS human gene, clicked the frist hit, went to FAST and copied the FAST sequence ( Made sure it started with: >NC). 
Then i opened the BLAST ( https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastn&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome) and used the nucletide BLAST [BLASTN] , pasted the FAST sequence and changed the database to nucleotide collection (nr/nt) and pressed BLAST seacrh botton at the end of the page. 
Waited for the site to respond.
Then checked the Query length (= gene length?) and then checked the Description/ Alignment/ Graphic Summary line) and clicked the Description. 
Scrolled down and found the hits. copared the homo spaience paralogs and the orthologs of the top 2 species ( pan trogloglydes and gorilla gorilla). And asnswered the quetions on our workbook. 
It was interesting to see the different versions of insulin genes and also how similar this gene was with potential ancestors of ours , that showed how importnt this gene is for survival and thus is naturally conserved gene. 

Day 2-
I searched in (https://www.ensembl.org), changed species to human, and searched for the INS (insulin gene), and clicked the first result with Ensembl Gene ID : ENSG00000254647 [made sure it started with ENS...]. 
Then found the location (choromose 11) and then checked the start - end of gene (2,159,779-2,161,221, and noticed it is the reversed stracnd (-). Subtracted the difference between start-end position and got 1442 bp gene length. 
Then clicked on the "3 exon" link and found the table with the start -end of each exon and intron and checekd which intron has the 5' UTR. 
Calculated the length of each exon as the difference start- end + 1 because it is inclusive ( starts form 1 not 0)
Then opend USCS Genome Browser Visualisation (https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr11%3A2153285%2D2167714&hgsid=4098546561_TYZ9k5maVdBZ7oVnCzqqAnSb7btr) and pasted there the locatin of the gene found in NCBI gene. Then zoomed out 10x and made a note of the genes on the left and the right.
Afterwards, i checked the peaks on the line above the different species and compared with the locations of the exons. In our eercise they were highly compatible whcih showed revolutionary importance and conservation of the insulin gene among differnet species. 
Lastly we go to ClinVar ( https://www.ncbi.nlm.nih.gov/clinvar) and on the Gene search bar i added 'INS', then More search options on other terms and write 'pathogenic', then search. 
ClinVar shows first large chromosome duplications, not individual mutations --> need to use filters on the left (under molecular sequence). 
Chose 'pathogenic' and 'missense'.
I chose a mutation that changes Gly --> Ser showing it is a missense mutation 
