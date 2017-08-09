# README

*Included files:*
1) ultimate.R // full analysis for flowFISH bins
2) intersect.R // intersects replicates
3) power.R // power calculations
4) accuracy.R // accuracy calculations


To run analysis:
1. use GridEngine8
2. qrsh -l virtual_free=8G
3. use .r-3.2.0-bioconductor-3.1; R_LIBS_SITE=; reuse Python-2.7
4. Rscript ultimate.R 
--wd [working directory] 
--designDocLocation [design document location] 
--countsLocation [counts location] 
--repSortParamsloc [sort parameters location] 
--output1 [output file name]

ex:
Rscript ultimate.R --wd /home/unix/tpatward/00EditAllTheScreens --designDocLocation /home/unix/tpatward/00EditAllTheScreens/161128.GATA1.24h/Design.txt --countsLocation /home/unix/tpatward/00EditAllTheScreens/161128.GATA1.24h/Counts.txt --repSortParamsloc /home/unix/tpatward//00EditAllTheScreens/161128.GATA1.24h/sortParams/1.txt --output1 tryNewer3


