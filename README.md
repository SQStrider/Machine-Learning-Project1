# Project1:Titanic Survival Exploration
* 该工程的主要目的是对泰坦尼克号的幸存者进行调查，我运用了决策树和随机森林的方法完成该项目。
## **特征Features**
- `pclass` : Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
- `name` : Name
- `sex` : Sex
- `age` : Age
- `sibsp` : Number of Siblings/Spouses Aboard
- `parch` : Number of Parents/Children Aboard
- `ticket` : Ticket Number
- `fare` : Passenger Fare
- `cabin` : Cabin
- `embarked` : Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
------------------------------------------------------------------------------------------------------
## 1.[决策树](titanic_survival_exploration1.ipynb)
    在使用决策树过程中，我通过观察各个特征乘客的幸存与死亡人数发现，女性以及年龄小于10岁的乘客幸存率最高，其次是兄弟姐妹较少并双亲健在的10~20岁青年，此外，乘坐头等舱的乘客的幸存率也相对较高。
    利用上述观察所得发现最终建立的模型，预测准确性可达80.13%
## 2.[随机森林](titanic_survival_exploration2.ipynb)
