# 天池城市计算挑战赛 23/2300 B榜
## 特征提取
1. progress_2系列,时刻附近流量统计
2. progress_3系列,站台/刷卡类型等特征
3. progress_4系列,周期及非周期用户特征
4. progress_5系列,出站分布特征,没有用
5. progress_6系列,天气
# 模型预测
## lgb_1_进站.ipynb
### 思路
用周六预测周日成为model1,上周日预测下周日成为model2,最后等权重融合.同时对数据每一分钟都计算一个十分钟间隔,倍增10倍数据.
