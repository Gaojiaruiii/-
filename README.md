## 中风患者的发病模式是什么?

### 成员

- 刘晓雨（3220200921）
- 刘晓晨（3220200920）
- 高佳蕊（3520200005）
- 吴林涛（3520190042）

### 问题描述

#### 1、问题背景及分析

​        据WHO(世界卫生组织)称：中风，亦称卒中，是全球第二大死亡原因，约占总死亡人数的11%。中风是一种严重可怕的心脑血管疾病，病情轻微，会导致不同程度的丧失劳动能力，病情严重的会有致残风险，甚至会有生命危险。

​        事实上，80%的中风是可以预防的。在本工作中，我们试图将一些导致中风的关键指标形象化。这里的数据是从各种年龄组、性别、习惯和与健康有关的问题中抽取的。我们的目的是可视化各种健康和不健康习惯与中风之间的关系，并通过最佳模型和超调参数预测来中风概率。

#### 2、问题描述

2.1 数据准备

​       我们选用来自kaggle的数据集Stroke Prediction Dataset（https://www.kaggle.com/fedesoriano/stroke-prediction-dataset），该数据集用于根据输入参数(如性别、年龄、各种疾病和吸烟状况)预测患者是否可能患中风。数据中的每一行都提供有关患者的相关信息。

​        首先将进行数据加载、缺失值可视化和特征提取。在当前数据集中，有11个特征和一个二进制目标。下面给出了有关这些特性的简要信息：

| **Attribute**         | **Description**                                            |
| --------------------- | ---------------------------------------------------------- |
| **id**                | Identification number of the individual                    |
| **gender**            | Gender of the individual                                   |
| **hypertension**      | Health related parameter, does person have hypertension    |
| **heart_disease**     | Health related parameter, does person have heart disease   |
| **ever_married**      | Personal information, is person married on not?            |
| **work_type**         | Nature of work place                                       |
| **Residence_type**    | Residence type of the individual                           |
| **avg_glucose_level** | average glucose level in blood for the individual          |
| **bmi**               | body mass index of the individual                          |
| **smoking_status**    | Habitual information. Current smoking status of individual |
| **stroke**            | Our taget, is person suffered heart attack?                |

2.2 采用的方法或模型

- 采样：随机采样，过采样，欠采样
- 分类模型：SVC，随机森林，Logistic回归，决策树，KNeighbors等进行对比分析

​       

2.3 挖掘结果

​       根据输入参数(如性别、年龄、各种疾病和吸烟状况)预测患者是否可能患中风

### 项目评估

1. 数据获取和清洗的完整性和有效性
2. 通过计算准确率和召回率，获取F1得分，AUC等

### 项目分工

- 刘晓晨（3220200920）：选题及数据获取，挖掘任务整理，系统设计，文档编写
- 高佳蕊（3520200005）：数据预处理，仓库管理，文档编写
- 吴林涛（3520190042）：训练模型，模型优化，文档编写
- 刘晓雨（3220200921）：相关实验，可视化分析实验结果





