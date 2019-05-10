### Description
Uae API to get fusion transcript sequence for probe design with 512 fusion, from COSMIC database  

Instruction in COSMIC:  
TMPRSS2 from exon 1 (UTR) to ERG exon 2 (inclusive).   
TMPRSS2{NM_005656.2}:r.1_71_ERG{NM_004449.3}:r.38_3097    
TMPRSS2 from intron after exon 1 to intron before ERG exon 2, intronic breakpoints known (374bp downstream of TMPRSS2 exon 1 and 54bp upstream of ERG exon 2).   
TMPRSS2{NM_005656.2}:r.1_71+374_ERG{NM_004449.3}:r.38-54_3097  
TRMPSS2 from intron after exon 1 to intron before ERG exon 2, intronic breakpoints NOT known (but remarked on in the paper).  
TMPRSS2{NM_005656.2}:r.1_71+?_ERG{NM_004449.3}:r.38-?_3097  


Mutation Id - links to the fusion summary page for more details of the inferred breakpoint.  
Gene Name - 5' partner gene involved in the fusion.  
Last Observed Exon - The last exon observed before the fusion breakpoint. In the 5' gene it can be ‘UTR’ or have ‘?’ if the breakpoint is unknown.  
Inferred breakpoint - mRNA breakpoint position in the 5'gene. A '+' followed by a number denotes a breakpoint downstream of the mRNA position given (in an intron or UTR). If the number is in parentheses the position is approximate.  
Gene Name - The 3' partner gene involved in the fusion.  
First Observed Exon - The first exon observed after the fusion breakpoint in the 3' gene. It can be ‘UTR’ or have ‘?’ if the breakpoint is unknown.  
Inferred breakpoint - mRNA breakpoint position in the 3'gene. A '?' indicates that the precise breakpoint is unknown. A '-' followed by a number denotes a breakpoint upstream of the mRNA position given (in an intron or UTR). If the number is in parentheses the position is approximate.  
Mutations - Number of unique samples found with this mutation.  
Mutation Frequency - Frequency (as a percentage) of mutated samples / total number of samples with this mutation.  



