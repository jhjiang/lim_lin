
## 《Theory of Logical Information Model & Logical Information Network》

> This is a paper on a whole new information model.
Because of the strong logicality of this information model, it can make up for the common problems of interpretability and causal reasoning in the existing artificial intelligence systems.

It involves:
### Logic
It is closer to traditional logic, and only absorbs some basic concepts in the domain of logic as its core.
It is fully compatible with mathematical logic.

### Artifical Intelligence
It is logicism but not symbolism, or connectionism.
It is closer to symbolism, and can be used as the data infrastructure of the new generation of knowledge base or knowledge repository and combined with expert systems.
However, it can also be combined with connectionism, and become the next research object of graph neural network because of its intrinsic properties of graph structure.

### Information Science
It is a new kind of information model which combines the most basic elements of logic.
Meanwhile, the infrastructure of this model is also based on graph structure. To some extent, it can be regarded as the upgraded form of knowledge graph model (or semantic network model).



## Structure of the article:

1. Introduction

2. Logical Model
  - 2.1 Argument-Proposition Model
    - 2.1.1 Argumentation & Proposition
    - 2.1.2 Naive Argument-Proposition Model
    - 2.1.3 Complex Argument-Proposition Model
  - 2.2 Definition & Narration
    - 2.2.1 Definition
    - 2.2.2 Narration
  - 2.3 Truth-Value of Proposition & Validity of Argument
    - 2.3.1 Truth-Value of Proposition
    - 2.3.2 (Special) Validity of Argument
  - 2.4 Condition
    - 2.4.1 Condition of Proposition
    - 2.4.2 Condition of Argument
  - 2.5 Reconsider Concept
    - 2.5.1 Concept & Definition
    - 2.5.2 Concept & Proposition

3. Information Model
  - 3.1 Doubt & Explanation
  - 3.2 Proposer & Observer
    - 3.2.1 Proposer & Observer
    - 3.2.2 Declaration of Proposer & Response of Observer
  - 3.3 Information Unit
    - 3.3.1 Information Unit
    - 3.3.2 Atomicity
    - 3.3.3 Assembling & Disassembling
  - 3.4 Information Relation
    - 3.4.1 Mapping Relation
    - 3.4.2 Equivalence Relation
    - 3.4.3 Causality Relation
    - 3.4.4 Defining Relation
    - 3.4.5 Other Relations
  - 3.5 Information Section
    - 3.5.1 Fusing
    - 3.5.2 Information Section
    - 3.5.3 Separating

4. Logical Information Model
  - 4.1 Completeness
    - 4.1.1 Completeness Extension of Statement
  - 4.2 Correspondence
    - 4.2.1 Correspondence between Conceptual Connotation and Words
    - 4.2.2 Correspondence between the Keys and Values of Attribute
  - 4.3 Conversion
    - 4.3.1 Serialization
      - 4.3.1.1 Serialization of Argument
      - 4.3.1.2 Serialization of Doubt
      - 4.3.1.3 Other Serializations
      - 4.3.1.4 Deserialization
    - 4.3.2 Symbolization
      - 4.3.2.1 Symbolization of Truth-Value of Proposition
      - 4.3.2.2 Symbolization of Validity of Argument
    - 4.3.3 Conversion between D&E and Inference

5. Logical Information Network: Characteristics
  - 5.1 Fragmentization
  - 5.2 Hierarchicalization
  - 5.3 Networking
  - 5.4 Quantifiability
    - 5.4.1 Quantifiability
    - 5.4.2 Redundancy
    - 5.4.3 Knowledge Measurement
  - 5.5 Visualization

6. Logical Information Network: Advanced Capabilities
  - 6.1 Logic Capabilities
    - 6.1.1 Logicality
    - 6.1.2 The Risk of Reasoning Paradox in Scientific Axiom System
    - 6.1.3 (General) Validity of Argument
    - 6.1.4 Expanding & Collapsing
  - 6.2 Information Capabilities
    - 6.2.1 Static Information
    - 6.2.2 Dynamic Information
    - 6.2.3 Hierarchy Dividing & Classifying of Domain Information
  - 6.3 Act

7. Logical Information Network: Significance
  - 7.1 Scientific Research & Popularization
    - 7.1.1 Scientific modeling
    - 7.1.2 Interdisciplinary Research
    - 7.1.3 Science Popularization
  - 7.2 Cognition
    - 7.2.1 Reading
    - 7.2.2 Memory
    - 7.2.3 Artificial Intelligence

8. Logical Information Network: Unsolved Problems

9. Summary

10. Acknowledgments

Appendix A. The view design scheme of logical information model

Appendix B. References


> From Chapter 2 to Chapter 5 is the basic part of the model, from shallow to deep;
Chapter 6 "Advanced Capabilities" is the core of the whole article, in which the most important ideas I want to express in this article are basically reflected;
Chapter 7 is the prospect of applications and some ideal application scenarios.

---------


# 《逻辑信息模型与逻辑信息网络》

> 这是一篇关于全新的信息模型的论文。
因为这种信息模型所具备的强逻辑性，使其可以很好地弥补现有人工智能体系中所普遍存在的可解释性和因果推理缺陷等问题。

它涉及：
### 逻辑学
更接近传统逻辑，且仅汲取部分逻辑学领域的基本概念为核心；
完全可以兼容数理逻辑；

### 人工智能
逻辑主义，但不是符号主义，也不是连接主义；
更接近于符号主义，它可以作为新一代知识库的底层数据结构，与专家系统相结合；
但也可以与连接主义结合，因其本质上图结构的属性而成为图神经网络下一步的研究对象。

### 信息科学
一种全新的结合了一众逻辑学最基本要素的数据模型；
同时这种模型的底层还基于图结构，在某种程度上可以看作是知识图谱模型（或者说是语义网络模型）的升级形态。



## 论文结构：

一、引言

二、逻辑模型
  - 2.1  “论证-命题”模型
    - 2.1.1  论证与命题
    - 2.1.2  “论证-命题”简单模型
    - 2.1.3  “论证-命题”复杂模型
  - 2.2  定义与叙述
    - 2.2.1  定义
    - 2.2.2  叙述
  - 2.3  命题真值与论证有效性
    - 2.3.1  命题的真值
    - 2.3.2  论证的（狭义）有效性
  - 2.4  条件
    - 2.4.1  命题的条件
    - 2.4.2  论证的条件
  - 2.5  再谈概念
    - 2.5.1  概念与定义
    - 2.5.2  概念与命题

三、信息模型
  - 3.1  疑问与解答
  - 3.2  发起者与观察者
    - 3.2.1  发起者与观察者
    - 3.2.2  发起者申明与观察者响应
  - 3.3  信息元
    - 3.3.1  信息元
    - 3.3.2  原子性
    - 3.3.3  组合与拆解
  - 3.4  信息关系
    - 3.4.1  映射关系
    - 3.4.2  等价关系
    - 3.4.3  因果关系
    - 3.4.4  定义关系
    - 3.4.5  其它关系
  - 3.5  信息段落
    - 3.5.1  融合
    - 3.5.2  信息段落
    - 3.5.3  分解

四、逻辑信息模型
  - 4.1  完备
    - 4.1.1  陈述语句的完备拓展
  - 4.2  对应
    - 4.2.1  概念内涵与语词的对应
    - 4.2.2  属性键值的对应
  - 4.3  转化
    - 4.3.1  序列化
      - 4.3.1.1  论证的序列化
      - 4.3.1.2  疑问的序列化
      - 4.3.1.3  其它序列化
      - 4.3.1.4  反序列化
    - 4.3.2  符号化
      - 4.3.2.1  命题真值的符号化
      - 4.3.2.2  论证有效性的符号化
    - 4.3.3  问答推论转化

五、逻辑信息网络·特征
  - 5.1  碎片化
  - 5.2  层级化
  - 5.3  网络化
  - 5.4  可量化
    - 5.4.1  可量化
    - 5.4.2  冗余
    - 5.4.3  知识度量
  - 5.5  可视化

六、逻辑信息网络·复杂功能
  - 6.1  逻辑功能
    - 6.1.1  逻辑性
    - 6.1.2  科学公理体系中的推理悖论风险
    - 6.1.3  论证（广义）有效性
    - 6.1.4  展开与折叠
  - 6.2  信息功能
    - 6.2.1  静态信息
    - 6.2.2  动态信息
    - 6.2.3  领域信息分层与分级
  - 6.3  行为

七、逻辑信息网络·意义
  - 7.1  科学研究与普及
    - 7.1.1  科学建模
    - 7.1.2  跨领域研究
    - 7.1.3  科学普及
  - 7.2  认知
    - 7.2.1  阅读
    - 7.2.2  记忆
    - 7.2.3  人工智能

八、逻辑信息网络·待解问题

九、总结

十、致谢

附录一、模型视图设计方案

附录二、参考文献


> 其中，从第二章到第五章是模型的基础部分，由浅及深；
第六章“复杂功能”是整个文章的核心部分，作者在文中想要表达的最重要的一些思想基本上都体现在这一章的内容里；
第七章则是对于应用的展望，一些比较理想化的应用场景等等。

