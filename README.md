# JData
京东JData算法大赛-高潜用户购买意向预测入门程序(starter code) 完整复现版
------------

本主页实现一些京东算法大赛数据进行分析的基本流程。包括： 

- 数据清洗
- 数据分析
- 特征抽取
- 搭建模型
- 模型评估 

语言为Python2.7,工具主要采用pandas,numpy,matplotlib,sklearn,xgboost等。代码可以看看，但对新手帮助不大。最好的学习方法，还是实践。 

依次运行以下文件，你将得到复现结果：
- **a0_data_cleaning.ipynb**              数据清洗
- **a1_data_analysis.ipynb**              数据分析
- **a2_exlpore_potential_user.ipynb**     探索高潜用户行为

---
## 没有数据或复现遇到困难？
没关系，[russellcloud](http://russellcloud.com/welcome)助您两步实现上述复现。

### Step 1 
搞定一个平台账号，[点我](http://russellcloud.com/welcome)，创建名为`JData`的项目。

```
pip install -U russell-cli

```

### Step 2
克隆复现

```
git clone https://github.com/RussellCloud/JData.git
cd JData
russell login
russell init --name JData
russell run --mode jupyter --data 63edccc637314e4f829383c00327fe89
```
弹出熟悉的jupyter notebook，接着就可以愉快地点、点、点、复现啦。


---

参考资料：https://github.com/daoliker/JData








