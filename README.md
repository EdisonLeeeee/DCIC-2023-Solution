# DCIC-2023 科技金融应用：欺诈风险识别
+ A/B榜 0.890x 解决方案
+ B 榜排名 11/1594

# 方案介绍
+ 使用lgb树模型
+ 10折交叉验证，4个不同种子/划分

几个强特：
+ 借贷标记：0或1 （原数据有）
+ 退款标记：0或1（交易金额是否大于0）：这个特征可以和借贷标记构建类似的强特
+ 基于借贷标记和退款标记构建转入次数、转出次数等
+ TF-IDF特征
+ 各种groupby

# 其它开源解决方案
+ 0.889 [GoogleLLP/DCIC2023-Fraud-Risk-Identification](https://github.com/GoogleLLP/DCIC2023-Fraud-Risk-Identification)
+ 0.88x [ZS167275/DCID-2023](https://github.com/ZS167275/DCID-2023)
+ 0.877 [jiangxiaoshuaiya/2023DCIC](https://github.com/jiangxiaoshuaiya/2023DCIC)



# 比赛链接
https://www.dcic-china.com/competitions/10060/
