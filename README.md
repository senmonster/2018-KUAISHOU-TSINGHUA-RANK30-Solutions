# 2018-KUAISHOU-TSINGHUA-RANK30-Solutions

2018中国高校计算机大赛--大数据挑战赛rank30
第一次全身心投入的数据挖掘比赛，学到很多，意识到自己还有很多短板，继续加油！

## 文件说明

 1.fea_eng生成基础统计特征
 
 2.get_new_label 提取新label,除了将用户是否活跃作为label外，还提取了用户在未来七天内（第一次启动，第一次创建视频，第一次活跃）距离训练窗口最后一天的时间差作为label,以及未来七天在所有表的出现次数作为label
 
 3.lgb_predASfea 上面提取的label作为特征，由于测试集没有这些label,故为了防止数据泄露，用10折cv-predict产生新的特征
 
 4.ensemble模型融合

## 短板
 1. NN模型设计运用
 
 2. Genetic Alogrithm for Feature selection
 
 3. 模型融合
 
 4. 代码的效率有待提高
 
 5. checkout again

