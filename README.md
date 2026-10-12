# Awesome Asset Pricing: Theory & Empirical Methods
> 资产定价理论与实证方法完全指南：从数学底座到前沿实证的博士级知识体系与书单

---

## 📌 选书原则与导读说明

1. **核心宗旨**：贯通**资产定价理论（Theory）**与**实证方法（Empirical Methods）**的内在对偶逻辑，杜绝“纯数理推导脱离现实”与“纯因子挖掘缺乏理论根基”的双向脱节。
2. **语言与版本选择策略**：
   * **第一选择**：以世界学术界公认的顶级英文经典原著为主体，且**优先选择已在国内出版高质量中文译本的书籍**，便于中英对照研读，大幅提升研读效率。
   * **前沿补充**：对于部分在资产定价与计量前沿具有不可替代性、但国内尚未翻译出版的顶尖专著（如 Bali 因子实操、Singleton 动态结构估计、Hansen 计量），保留英文原版并明确标注。
3. **分级编号体系**：
   * `0` 核心专论（资产定价核心理论 / 经典实证方法）
   * `1` 工具与工程应用（金融工程 / 金融时间序列分析）
   * `2` 核心分析方法（随机分析微分方程 / 计量经济学与因果推断）
   * `3` 概率与数理统计（测度论概率论 / 统计推断与假设检验）
   * `4 - 6` 数学底座（数学分析、泛函分析、线性代数、拓扑与逻辑学）

---

## 🔗 理论与实证的对偶关系 (Dual Framework)

在现代资产定价体系中，理论推导与实证检验是一一对应的：

```text
[ Part I: 资产定价理论 ]                      [ Part II: 资产定价实证 ]
========================================================================================
效用理论与均值-方差均衡 (Fama / Cochrane)  <--->  截面多因子排序与 Fama-MacBeth 回归 (Bali et al.)
消费资产定价与贴现因子 (Cochrane / Campbell) <--->  广义矩估计 (GMM) 与 Hansen-Jagannathan 边界 (Hayashi / Singleton)
连续时间无套利与期限结构 (Duffie / Shreve)  <--->  仿射期限结构模型与卡尔曼滤波 MLE (Singleton / Tsay)
跨期资产配置与现值模型 (Campbell / Back)    <--->  VAR 收益率分解与贴现率新闻检验 (CLM / Tsay)
```

---

## 📚 第一部分：资产定价理论 (Asset Pricing: Theory)

### 0. 核心理论与金融经济学
* **0.1** 《金融基础：投资组合决策和证券价格》 | *Foundations of Finance* (1976)
  * 作者：Eugene F. Fama (尤金·法玛) | 译者：王蕾 等 | 【有中文译本】
* **0.2** 《现代投资组合理论与投资分析》原书第9版 | *Modern Portfolio Theory and Investment Analysis* (2014)
  * 作者：Edwin J. Elton, Martin J. Gruber 等 | 【有中文译本】
* **0.3** 《金融经济学二十五讲》 (2017)
  * 作者：徐高 | 【中文原创经典教材】
* **0.4** 《金融决策理论》 | *Theory of Financial Decision Making* (1987)
  * 作者：Jonathan E. Ingersoll, Jr. (小乔纳森·E·英格索尔) | 译者：杨墨竹 | 【有中文译本】
* **0.5** 《动态资产定价理论》第3版 | *Dynamic Asset Pricing Theory* (2001)
  * 作者：Darrell Duffie (达雷尔·达菲) | 译者：刘立新 等 | 【有中文译本】
* **0.6** 《资产定价》修订版 | *Asset Pricing* (2005)
  * 作者：John H. Cochrane (约翰·科克伦) | 译者：王蕾 等 | 【有中文译本】
* **0.7** 《资产定价理论》 | *Theory of Asset Pricing* (2008)
  * 作者：George Pennacchi (乔治·彭纳齐) | 译者：杨墨竹, 李凤羽 | 【有中文译本】
* **0.8** *Financial Asset Pricing Theory* (2013)
  * 作者：Claus Munk | 【英文原版 / 暂无中译本】
* **0.9** *Asset Pricing and Portfolio Choice Theory* 2nd ed. (2017)
  * 作者：Kerry E. Back | 【英文原版 / 暂无中译本】
* **0.10** 《金融决策与市场：资产定价教程》 | *Financial Decisions and Markets: A Course in Asset Pricing* (2018)
  * 作者：John Y. Campbell (约翰·Y·坎贝尔) | 【有中文译本】

### 1. 金融随机分析与衍生品工程
* **1.1.1** 《金融随机分析 第1卷：二叉树资产定价模型》 | *Stochastic Calculus for Finance I*
  * 作者：Steven E. Shreve | 译者：陈启宏, 陈迪华 | 【有中文译本】
* **1.1.2** 《金融随机分析 第2卷：连续时间模型》 | *Stochastic Calculus for Finance II*
  * 作者：Steven E. Shreve | 译者：陈启宏, 陈迪华 | 【有中文译本】
* **1.2** 《金融统计与数理金融：方法、模型及应用》 | *Financial Statistics and Mathematical Finance*
  * 作者：Ansgar Steland (斯特兰) | 【有中文译本】
* **1.3** 《金融衍生工具数学导论》 | *An Introduction to the Mathematics of Financial Derivatives*
  * 作者：Salih N. Neftci | 译者：艾利·赫萨 等 | 【有中文译本】
* **1.4** 《金融工程原理》 | *Principles of Financial Engineering*
  * 作者：Salih N. Neftci | 译者：陈典发 等 | 【有中文译本】
* **1.5** 《数理金融初步》原书第3版 | *An Elementary Introduction to Mathematical Finance*
  * 作者：Sheldon M. Ross (罗斯) | 译者：王德辉 等 | 【有中文译本】

### 2. 随机分析与随机微分方程
* **2.1** 《随机微分方程导论与应用》第6版 | *Stochastic Differential Equations: An Introduction with Applications*
  * 作者：Bernt Øksendal (厄克森达尔) | 译者：刘金山, 吴付科 | 【有中文译本】
* **2.2** 《随机积分导论》 | *Introduction to Stochastic Integration*
  * 作者：Kai Lai Chung (钟开莱), Ruth J. Williams | 【有中文译本】
* **2.3** 《鞅与随机微分方程》
  * 编著：王力, 李龙锁 | 【中文经典教材】

### 3. 概率测度与高等概率论
* **3.1** 《概率论基础教程》原书第9版 | *A First Course in Probability*
  * 作者：Sheldon M. Ross | 译者：郑忠国 等 | 【有中文译本】
* **3.2** 《随机过程》第2版 | *Stochastic Processes*
  * 作者：Sheldon M. Ross | 译者：何声武 等 | 【有中文译本】
* **3.3** 《应用随机过程》
  * 编著：李东凤 | 【中文经典教材】
* **3.4** 《实分析和概率论》原书第2版 | *Real Analysis and Probability*
  * 作者：R. M. Dudley | 【有中文译本】
* **3.5.1 & 3.5.2** 《测度论基础与高等概率论》(上/下册)
  * 编著：袁德美, 王学军 | 【中文系统专著】

### 4. 数学分析、流形几何与泛函分析
* **4.1.1 & 4.1.2** 《微积分及其应用》《多元微积分及其应用》 | *Calculus with Applications*
  * 作者：Peter D. Lax, Maria Terrell | 【有中文译本】
* **4.2** 《向量微积分、线性代数和微分形式统一方法》第5版 | *Vector Calculus, Linear Algebra, and Differential Forms*
  * 作者：John H. Hubbard, Barbara Burke Hubbard | 【有中文译本】
* **4.3** 《流形上的分析》 | *Analysis on Manifolds*
  * 作者：James R. Munkres (曼克勒斯) | 【有中文译本】
* **4.4** 《曲线与曲面的微分几何》 | *Differential Geometry of Curves and Surfaces*
  * 作者：Manfredo P. do Carmo (多卡尔莫) | 【有中文译本】
* **4.5** 《普林斯顿数学分析读本》 | *The Real Analysis Lifesaver*
  * 作者：Raffi Grinberg | 译者：李颖 | 【有中文译本】
* **4.6** 《陶哲轩实分析》第4版 | *Analysis I & II*
  * 作者：Terence Tao (陶哲轩) | 译者：李馨 | 【有中文译本】
* **4.7** 《数学分析》原书第2版 | *Mathematical Analysis*
  * 作者：Tom M. Apostol (阿波斯托尔) | 【有中文译本】
* **4.8** 《实分析》原书第4版 | *Real Analysis*
  * 作者：H. L. Royden (罗伊登), P. M. Fitzpatrick | 【有中文译本】
* **4.9** 《泛函分析导论及应用》 | *Introductory Functional Analysis with Applications*
  * 作者：Erwin Kreyszig (克雷斯齐格) | 【有中文译本】
* **4.10** 《微分方程与边界值问题》 | *Differential Equations with Boundary-Value Problems*
  * 作者：Dennis G. Zill (兹尔) | 【有中文译本】

### 5. 线性代数与抽象代数
* **5.1** 《线性代数及其应用》原书第5版 | *Linear Algebra and Its Applications*
  * 作者：David C. Lay | 译者：刘深泉 等 | 【有中文译本】
* **5.2** 《线性代数应该这样学》第4版 | *Linear Algebra Done Right*
  * 作者：Sheldon Axler | 译者：吴俊达, 何阳 | 【有中文译本】
* **5.3** 《线性代数及其应用》 | *Linear Algebra and Its Applications*
  * 作者：Peter D. Lax (拉克斯) | 译者：傅莺莺, 沈复兴 | 【有中文译本】
* **5.4** 《抽象代数基础教程》原书第3版 | *A First Course in Abstract Algebra*
  * 作者：Joseph J. Rotman | 译者：李祥明, 冯明军 | 【有中文译本】
* **5.5** 《代数》 | *Algebra*
  * 作者：Michael Artin (阿廷) | 【有中文译本】

### 6. 数学基础、拓扑与数理逻辑
* **6.1** 《集合论、拓扑与代数初步》
  * 编著：刘守民, 熊锐 | 【中文系统教程】
* **6.2** 《拓扑学》原书第2版 | *Topology*
  * 作者：James R. Munkres (芒克里斯) | 译者：程吉树 等 | 【有中文译本】
* **6.3** 《应用组合数学》原书第2版 | *Applied Combinatorics*
  * 作者：Fred S. Roberts, Barry Tesman | 【有中文译本】
* **6.4** 《逻辑学导论》第13版 | *Introduction to Logic*
  * 作者：Irving M. Copi, Carl Cohen | 译者：张建军 等 | 【有中文译本】

---

## 🔬 第二部分：资产定价实证方法 (Asset Pricing: Empirical Methods)

### 0. 核心实证专论
* **0.1** 《金融中的统计方法》 (1996) | *Handbook of Statistics 14: Statistical Methods in Finance*
  * 编著：G. S. Maddala (马达拉), C. R. Rao (拉奥) | 【有中文译本】
* **0.2** 《金融市场计量经济学》 (1997) | *The Econometrics of Financial Markets*
  * 作者：John Y. Campbell, Andrew W. Lo, A. Craig MacKinlay (CLM) | 译者：朱平芳 等 | 【有中文译本 / 金融计量圣经】
* **0.3** *Empirical Dynamic Asset Pricing: Model Specification and Econometric Assessment* (2006)
  * 作者：Kenneth J. Singleton (辛格尔顿) | 【英文原版 / 暂无中译本 / 动态结构实证顶峰】
* **0.4** *Empirical Asset Pricing: The Cross Section of Stock Returns* (2016)
  * 作者：Turan G. Bali, Robert F. Engle, Scott Murray | 【英文原版 / 暂无中译本 / 因子实操圣经】

### 1. 金融时间序列与应用
* **1.1** 《金融数据分析导论：基于R语言》 | *An Introduction to Analysis of Financial Data with R*
  * 作者：蔡瑞胸 (Ruey S. Tsay) | 译者：潘家柱 等 | 【有中文译本】
* **1.2** 《金融时间序列分析》第3版 | *Analysis of Financial Time Series*
  * 作者：蔡瑞胸 (Ruey S. Tsay) | 译者：王远林 等 | 【有中文译本】
* **1.3** 《多元时间序列分析及金融应用：基于R语言》 | *Multivariate Time Series Analysis with R and Financial Applications*
  * 作者：蔡瑞胸 (Ruey S. Tsay) | 【有中文译本】

### 2. 计量经济学基础与因果推断底座
* **2.1** 《计量经济学导论：现代观点》第6版 | *Introductory Econometrics: A Modern Approach*
  * 作者：Jeffrey M. Wooldridge (伍德里奇) | 译者：王忠玉 等 | 【有中文译本】
* **2.2** 《计量经济学》 | *Econometrics* (2000)
  * 作者：林文夫 (Fumio Hayashi) | 译者：冉启康, 朱保华 | 【有中文译本 / GMM 框架经典】
* **2.3** 《高级计量经济学》 (2011)
  * 作者：洪永淼 | 【中文前沿专著】
* **2.4** *Econometrics* (2022)
  * 作者：Bruce E. Hansen (布鲁斯·汉森) | 【英文原版 / 博士级现代计量集大成者】
* **2.5** 《因果推断与效应评估的计量经济学》 | *Econometrics of Policy Evaluation*
  * 作者：Markus Frölich, Stefan Sperlich | 【有中文译本】

### 3. 数理统计与严格假设检验
* **3.1** 《概率与统计面向经济学》 | *Probability and Statistics for Economists*
  * 作者：Bruce E. Hansen | 【有中文译本】
* **3.2** 《统计推断》第2版 | *Statistical Inference*
  * 作者：George Casella, Roger L. Berger | 译者：张忠占 等 | 【有中文译本】
* **3.3** 《数理统计》第2版 | *Mathematical Statistics*
  * 作者：邵军 (Jun Shao) | 【有中文译本】
* **3.4** 《概率论与统计学》
  * 作者：洪永淼 | 【中文系统专著】
* **3.5** 《现代非参数统计》 | *All of Nonparametric Statistics*
  * 作者：Larry Wasserman | 译者：吴喜之 等 | 【有中文译本】
* **3.6** 《点估计理论》第2版 | *Theory of Point Estimation*
  * 作者：E. L. Lehmann, George Casella | 译者：郑忠国 等 | 【有中文译本】
* **3.7** *Testing Statistical Hypotheses* 3rd ed.
  * 作者：E. L. Lehmann, Joseph P. Romano | 【英文原版 / 统计假设检验权威经典】
* **3.8** 《统计模拟》原书第5版 | *Simulation*
  * 作者：Sheldon M. Ross | 译者：王兆军 等 | 【有中文译本】

---

## 🎯 推荐阅读与进阶路径

* **第一阶段：因子实证与量化实操切入**
  * 理论线：`0.6 Cochrane` (精读第1-6章) 或 `0.3 徐高`
  * 实证线：`0.4 Bali et al.` + `1.2 Tsay`
  * 产出目标：掌握 Fama-French 多因子模型、投资组合双重排序、Fama-MacBeth 回归与 GARCH 波动率实操。
* **第二阶段：经典金融计量与稳健检验**
  * 理论线：`0.7 Pennacchi` + `0.10 Campbell (2018)`
  * 实证线：`0.2 CLM (1997)` + `2.2 Hayashi (GMM)`
  * 产出目标：深入理解 GRS 检验、事件研究法、Campbell-Shiller 收益率分解与大样本渐近理论。
* **第三阶段：动态结构模型与前沿数理**
  * 理论线：`0.5 Duffie` + `1.1 Shreve (Vol 2)` + `2.1 Øksendal`
  * 实证线：`0.3 Singleton (2006)` + `3.7 Lehmann`
  * 产出目标：掌握连续时间测度变换（$\mathbb{P}$ 到 $\mathbb{Q}$）、仿射期限结构实证拟合与多重假设检验校正。

---

## 📄 免责声明 (Disclaimer)

本仓库仅提供书目推荐、学术导读与学习路线规划，不提供任何未经授权的电子书下载。书中涉及学术成果版权均归原作者及出版社所有，请支持正版学术著作。
