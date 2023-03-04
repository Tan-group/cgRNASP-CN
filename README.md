# cgRNASP-CN

Coarse-grained statistical potential involving two CG beads at  C4’,N1/N9.

```
# Compilation and usage under linux

gcc cgRNASP-CN.c -lm -o cgRNASP-CN

# Run in the example dir

 N=`ls *.pdb | wc -l`
 ./cgRNASP-CN ./ ${N} energy_list.txt

# Output:
   
# 4_adamiak_1_rpr.pdb     -450.422337 kBT
# 15_3dRNAAS2_2_rpr.pdb   -168.510059 kBT

Note: the subfolder "data/" and compiled "cgRNASP-CN" should be in the same folder.
```
Please feel free to contact us if you have any question! zjtan@whu.edu.cn

Reference:                                      
[1]  Song L, Yu S, Wang X, Tan YL, & Tan ZJ. 2022. cgRNASP-CN: a minimal coarse-grained representation-based statistical potential for RNA 3D structure evaluation. Commun Theor Phys, 74(7): 075602.
