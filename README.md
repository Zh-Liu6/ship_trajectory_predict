# 使用铜锣峡3月-9月的数据训练模型
## 其中船舶可能多次通过该水道，按照时间将同一条船舶多次通过铜锣峡水道的轨迹划分，并用traject_id标记船舶通过一次铜锣峡水道的轨迹
### 将tlx0910.csv中的数据分为训练集和测试集
### 使用LSTM预测，每10个点预测一个值，然后再使用预测出的值进行预测
