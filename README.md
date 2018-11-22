# ANZ_Chengdu_rank4_solution
澳新银行数据竞赛（DC平台）第四名方案

竞赛地址：http://www.pkbigdata.com/common/cmpt/ANZ%20Chengdu%20Data%20Science%20Competition_%E7%AB%9E%E8%B5%9B%E4%BF%A1%E6%81%AF.html?lang=en_US  
数据：https://pan.baidu.com/s/1tkCG1jlLfEo49sgGaBy72Q  Password：j52p   

# 方案思路

**1.数据分析**  

     *分析每个特征的分布情况，可找到的数据分布特点。 
     *分析特征和目标特征的相关情况，对构建特征的指导意义。  
     *缺失特征情况展示。  
     *PCA降维分析图  
     
**2.数据预处理**  

     *重要且缺失少的特征的补全  
     *类型转编码  
**3.特征工程**

     *构建分箱离散化特征  
     *构建交叉特征  
     *构建排序特征  
     *使用贪心+模型法进行特征筛选  
     *使用贪心+皮尔顿相关系数去除高相关性特征  
**4.模型融合**  

     *lgb模型  
     *xgb模型  
     *GBDT模型  
     *NN+GBDT模型  
     *GBDT+LR模型  
     *五种模型的加权融合  
     
     
后记：这次比赛的时间只有两周时间，所以时间很紧张，很多部分并没有做到尽致，不过我们已经尽出全力，只可惜未能得奖，希望下场比赛能得奖而归。  
