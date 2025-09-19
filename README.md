# 《蛋白质：从一条序列出发》
专为**蛋白质模型质量评估**领域新手打造的入门学习乐园

Protein-Model-Quality-Assessment-Guide-for-Beginners
<br>

## 基于docs/review 中的2023和2024的综述进行梳理
### 方法梳理
| 方法类型   | 方法名称        | 开发团队 / 开发者   | 对应文献 |
|------------|-----------------|---------------------|----------|
| 共识方法   | MULTICOM 系列   | Cheng 课题组        | [1][2][3] |
|           | MUfoldQA 系列   | Xu 和 Shang 课题组  | [4][5] |
|           | ModFOLDclust2   | McGuffin            | [6] |
|           | QDistance(Yang_TBM) | 杨建益课题组        | [7] |
|           | clustQ          | Bhattacharya 课题组 | [8] |
|           | Pcons           |                     | [9] |
|           | APOLLO          |                     | [10] |
| 准单模型方法 | ModFOLD 系列    | McGuffin 课题组     | [11][12][13] |
|           | QMEANDisco      |                     | [14] |
| 单模型方法 | DeepAccNet 系列 | Baker 课题组        | [15] |
|           | ProQ 系列       | Elofsson 课题组     | [16][17][18][19][20] |
|           | Voro 系列       | Venclovas 课题组    | [21][22][23] |
|           | Yang_TBM        | 杨建益课题组        | [24] |
|           | DeepUMQA 系列   | 张贵军课题组        | [25][26][27] |
|           | AlphaFold2      | DeepMind 团队       | [28] |
|           | GraphQA         |                     | [29] |
|           | Qdeep           |                     | [30] |
|           | Ornate          |                     | [31] |
|           | AngularQA       |                     | [32] |
|           | 3DCNN           |                     | [33] |
|           | QAcon           |                     | [34] |
|           | SVMQA           |                     | [35] |
|           | DeepQA          |                     | [36] |
|           | QMEAN           |                     | [37] |
|           | ProSA           |                     | [38][39] |

### 指标梳理
<div align=center>
<img width="1000" src="/docs/images/0_0.png"/>
</div>
<div align=center>蛋白质结构模型质量评估指标表</div>
<br>

## 参考引用
[1] Wang Z, Eickholt J, Cheng J L. 2010. Bioinformatics, 26, 882.  
[2] Cheng J L, Wang Z, Tegge A N, Eickholt J. 2009. Proteins: Structure, Function, and Bioinformatics, 77, 181.  
[3] Wu T Q, Guo Z Y, Hou J, Cheng J L. 2021. BMC Bioinformatics, 22.  
[4] Wang J L, Wang W B, Shang Y, Xu D. 2022. IEEE 4th International Conference on Cognitive Machine Intelligence (CogMI), pp. 84, Las Vegas, NV, USA & Changsha, China.  
[5] Wang W B, Li Z Y, Wang J L, Xu D, Shang Y. 2019. Nucleic Acids Research, 47, W443.  
[6] McGuffin L J, Roche D B. 2010. Bioinformatics, 26, 182.  
[7] Ye L S, Wu P K, Peng Z L, Gao J Z, Liu J, Yang J Y. 2021. Bioinformatics, 37, 3752.  
[8] Alapati R, Bhattacharya D. 2018. Proceedings of the 2018 ACM International Conference on Bioinformatics, Computational Biology, and Health Informatics, pp. 307, Washington DC, USA.  
[9] Lundström J, Rychlewski L, Bujnicki J, Elofsson A. 2001. Protein Science, 10(11), 2354–2362.  
[10] Wang Z, Eickholt J, Cheng J L. 2011. Bioinformatics, 27(12), 1715–1716.  
[11] McGuffin L J, Aldowsari F M, Alharbi S M, Adiyaman R. 2021. Nucleic Acids Research, 49, W425.  
[12] McGuffin L J, Buenavista M T, Roche D B. 2013. Nucleic Acids Research, 41, W368.  
[13] McGuffin L J. 2008. Bioinformatics, 24, 586.  
[14] Studer G, Rempfer C, Waterhouse A M, et al. 2020. Bioinformatics, 36(6), 1765–1771.  
[15] Hiranuma N, Park H, Baek M, Anishchenko I, Dauparas J, Baker D. 2021. Nature Communications, 12, 1340.  
[16] Uziela K, Menéndez Hurtado D, Shu N, Wallner B, Elofsson A. 2017. Bioinformatics, 33(10), 1578–1580.  
[17] Uziela K, Wallner B. 2016. Bioinformatics, 32(9), 1411–1432.  
[18] Ray A, Lindahl E, Wallner B. 2012. BMC Bioinformatics, 13, 224.  
[19] Basu S, Wallner B. 2016. Bioinformatics, 32(12), i262–i270.  
[20] Uziela K, Shu N, Wallner B, Elofsson A. 2016. Scientific Reports, 6, 33509.  
[21] Olechnovič K, Venclovas Č. 2017. Proteins: Structure, Function, and Bioinformatics, 85, 1131.  
[22] Olechnovič K, Venclovas Č. 2019. Nucleic Acids Research, 47, W437.  
[23] Igashov I, Olechnovič K, Kadukova M, Venclovas Č, Grudinin S. 2021. Bioinformatics, 37, 2332.  
[24] Ye L S, Wu P K, Peng Z L, Gao J Z, Liu J, Yang J Y. 2021. Bioinformatics, 37, 3752.  
[25] Guo S S, Liu J, Zhou X G, Zhang G J. 2022. Bioinformatics, 38, 1895.  
[26] Liu J, Liu D, He G X, Zhang G J. 2023. Proteins: Structure, Function, and Bioinformatics, 91, 1861.  
[27] Liu J, Zhao K L, Zhang G J. 2023. Briefings in Bioinformatics, 24, bbac507.  
[28] Jumper J, Evans R, Pritzel A, et al. 2021. Nature, 596, 583–598.  
[29] Baldassarre F, Menéndez Hurtado D, Elofsson A, Azizpour H. 2021. Bioinformatics, 37(3), 360–366.  
[30] Shuvo M H, Bhattacharya S, Bhattacharya D. 2020. Bioinformatics, 36(Suppl 1), i285–i291.  
[31] Pagès G, Charmettant B, Grudinin S. 2019. Bioinformatics, 35(18), 3313–3319.  
[32] Conover M, Staples M, Si D, et al. 2019. Computational Mathematics and Biophysics, 7(1), 1–9.  
[33] Derevyanko G, Grudinin S, Bengio Y, Lamoureux G. 2018. Bioinformatics, 34(23), 4046–4053.  
[34] Cao R Z, Adhikari B, Bhattacharya D, et al. 2017. Bioinformatics, 33(4), 586–588.  
[35] Manavalan B, Lee J. 2017. Bioinformatics, 33(16), 2496–2503.  
[36] Cao R Z, Bhattacharya D, Hou J, Cheng J L. 2016. BMC Bioinformatics, 17(1), 495.  
[37] Benkert P, Tosatto S C, Schomburg D. 2008. Proteins, 71(1), 261–277.  
[38] Sippl M J. 1993. Proteins, 17(4), 355–362.  
[39] Wiederstein M, Sippl M J. 2007. Nucleic Acids Research, 35(Web Server issue), W407–W410.  
