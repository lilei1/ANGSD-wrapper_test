# ANGSD-wrapper_test
- How to produce rand1000_region.bed?
- use this commanline: 0.00563574 = 1000 regions / total regions in "Covered_Regions.bed"
perl -ne 'print if (rand() < 0.00563574)' /home/morrellp/llei/Shared/shared/Datasets/Annotations/Barley_ExCap_Sequenced_Regions/Covered_Regions.bed > rand1000_region.bed 

