## MIMIC III & IV 下载、数据库安装、可视化管理



#### Section 1 数据集详情和下载

1. MIMIC III 的官方论文在[这里](https://www.nature.com/articles/sdata201635)，MIMIC IV的官方论文在[这里](https://www.nature.com/articles/s41597-022-01899-x)，请事先进行阅读并理解该数据集的详情。
2. MIMIC III & MIMIC IV 的官网documentation 可以访问[这里](https://mimic.mit.edu/docs/iii/)以及[这里](https://mimic.mit.edu/docs/iv/)。
3. 两者的数据集下载地址在[III](https://physionet.org/content/mimiciii/1.4/)和[IV](https://physionet.org/content/mimiciv/3.0/)，**数据请带U盘(>64GB) 在我这边拷贝获取**。没有的话，我这边提供U盘临时拷贝。目前只有III版本，IV版本正在下载。



#### Section 2 Postgres数据库构建（windows)

**全程跟随官方网站的[教程](https://mimic.mit.edu/docs/gettingstarted/local/install-mimic-locally-windows/)进行安装！！**

1. 安装PostgreSQL
2. 跳过（optional 环节）
3. 进行shell SQL的设置（Run SQL shell）

完成后，可以test 是否成功，成功后即可进行下一阶段。



#### Section 3 NaviCAT安装和导入数据库

1. 从淘宝上购买Navicat premium 16版本的激活码，并安装软件激活。
2. 打开软件并导入section 2 安装好的数据库，详情可以参考这篇[博客](https://blog.csdn.net/qq_44297664/article/details/129530466)。
3. 可以自行使用SQL语言（可以使用GPT进行辅助）进行查看测试。





### 建议阅读：

#### 方向一：术中低血压预测

| 序号 | 标题 | 大致内容 |
| ---- | ---- | -------- |
|      |      |          |
|      |      |          |
|      |      |          |

#### 方向二：急性肾损伤

| 序号 | 标题 | 大致内容 |
| ---- | ---- | -------- |
|      |      |          |
|      |      |          |
|      |      |          |

#### 方向三：ICD疾病编码

| 序号 | 标题                                                         | 大致内容 |
| ---- | ------------------------------------------------------------ | -------- |
| 1    | CoRelation: Boosting Automatic ICD Coding Through Contextualized Code Relation Learning |          |
| 2    | A Two-Stage Decoder for Efficient ICD Coding                 |          |
| 3    | Multi-Label Few-Shot ICD Coding as Autoregressive Generation with Prompt |          |
| 4    | Towards Semi-Structured Automatic ICD Coding via Tree-based Contrastive Learning |          |
| 5    | A Unified Review of Deep Learning for Automated Medical Coding |          |
| 6    | Automated Medical Coding on MIMIC-III and MIMIC-IV: A Critical Review and Replicability Study |          |
| 7    | Knowledge Injected Prompt Based Fine-tuning for Multi-label Few-shot ICD Coding |          |



其他

