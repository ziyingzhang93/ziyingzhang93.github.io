# GSEA和ssGSEA 

参考：https://www.youtube.com/watch?v=ElJ4IAQxwaE

图片
![image](https://github.com/user-attachments/assets/cafef7b8-2758-4a11-ab23-40c333b836b8)


Class B - Tumor

ClassA - Normal

Tumor 相对于Normal的DEGs的 logFoldChange从大到小排序， 或者p-value 更显著的排在前面，然后不同的Gene Set 的gene 去一个个对应顺序，加减分得倒一个富集分数。

图片
![image](https://github.com/user-attachments/assets/b690566b-b32d-48a0-b257-be5c8f92cbeb)


从左到右是logFC排序从大到小的基因总列表，gene set内出现的加分，剩下的减分，最终达到一个最高点。

---------------------------------------

ssGSEA 是GSEA的扩展，不需要两两组进行比较，每一个样本内部，都可以对不同的免疫细胞或其他细胞有个富集分数。
