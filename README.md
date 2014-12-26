The thesis submitted to XIDIAN UNIVERSITY for the degree of Master,  
the main content of this thesis is summarized as follows:

The first part focuses on solving the problem of abuse using of running  
memory when computing suffix array,we develop a lightwight construction  
DCV,the result is comparative with LS.

In the second part,we develop two practical CSA(compressed suffix array)  
structuress,called Gam-CSA and Adaptive-CSA.We partion the gap sequence  
of Phi array into blocks and use gamma coding,data-aware coding for  
Gam-CSA and Adaptive-CSA respectively.Experiments show significant  
advantages over other CSAs.

In the last part,we designe an efficient FM-index,called Adaptive-FM,use  
a versatile structure,i.e.,WT(wavelet tree).The BitMap within WT is parted  
into blocks and using data-aware rank for each block, just like the way in  
Adaptive-CSA.Experiments show significant advantages,especially in space.  

CSAs and FMs:  
 [Gam-CSA](https://github.com/chenlonggang/Compressed-Suffix-Array)  
 [Adaptive-CSA](https://github.com/chenlonggang/Adaptive-CSA)  
 [Adaptive-FM](https://github.com/chenlonggang/Adaptive-FM-index)  
 [Sad-CSA](http://pizzachili.dcc.uchile.cl/indexes/Compressed_Suffix_Array/)  
 [RLCSA](http://pizzachili.dcc.uchile.cl/indexes/RLCSA/)  
 [PR-FM](http://pizzachili.dcc.uchile.cl/indexes/FM-indexV2/)  
 [SDSL-libs](https://github.com/simongog/sdsl-lite)  

Data compress software Based on CSA or FM:  
[Czip](https://github.com/chenlonggang/Czip)  
[Wzip](https://github.com/chenlonggang/wzip) 32-bit platform only  

