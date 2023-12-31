# Chapter 2

---

软件工程学科的定义：

1. 将系**统化的、规范的、可量化**的方法应用于软件的**开发、运行和维护**，即将工程化方法应用于软件；
2. 对于（1）中所述方法的研究。

![Software engineering layers](/软件工程/img/Software%20engineering%20layers.png)

- 支持软件工程的根基在于**质量关注点** （quality focus）
- 软件工程的基础是**过程层**（process）
- 软件过程构成了软件项目管理控制的基础。
- 软件工程**方法** ，为构建软件提供技术上的解决方法（如何做）。
- 软件工程**工具**为过程和方法提供自动化或半自动化的支持。
  
  ```
  计算机辅助软件工程（computer-aided software engineering(CASE)）
  将软件工程工具集成起来，使得一个工具产生的信息可被另外一个工具使用，这样就建立起了软件开发的支撑系统，称为计算机辅助软件工程。
  ```

软件的质量是在**软件开发的过程**中形成的。  

# 软件过程（the software process）

定义：软件过程是工作产品构建时所执行的一系列**活动、动作和任务**的集合。  

- 活动主要实现宽泛的目标。
- 动作包含了主要工作产品生产过程中的一系列任务。
- 任务关注小而明确的目标，能够产生实际产品。

## 过程框架（process framework）

一个通用的软件工程过程框架通常包含以下5个活动：  

- **沟通** 
- **策划**
- **建模**：需求建模+设计建模  
- **构建**：编码+测试
- **部署**

在项目的多次迭代过程中，沟通、策划、建模、构建、部署等活动不断重复。每次项目迭代都会产生一个**软件增量**，每个软件增量实现了部分的软件特性和功能。  

随着每一次增量的产生，软件将逐渐完善。

---

## 普适性活动（Umbrella Activities）

软件工程过程框架活动由很多普适性活动来补充实现。  

普适性活动包括：

- 软件项目跟踪和控制（Software project planning,tracking and control）
- 风险管理(Risk management)
- 软件质量保证(Software quality assurance)
- 技术评审(Technical reviews)
- 测量(Measurement)
- 软件配置管理(Software configuration management)
- 可复用管理(Reusability management)
- 工作产品的准备和生产(Work product preparation and production)

### 风险管理 risk management的完整过程(重要，会考🌟)

1. **识别风险（identity work）**: 经验(experience)，头脑风暴（brainstorming），专家系统（repository）**【以上是识别风险的三个方法】**  
   
   ```risk exposure=prob(风险发生的概率)*lose（风险发生的损失）```

2. **规避风险的计划 (risk avoiding plan)** 
   
3. **追踪风险(tracking risk)** 

### 软件配置管理 Software configuration management

软件配置管理（Software Configuration Management，SCM）是指管理和控制软件系统开发、部署和维护过程中的配置项（Configuration Item，CI）的活动和实践。它涉及对软件系统的**源代码、二进制文件、文档、库文件、构建配置、测试数据等**进行**版本控制、变更管理、构建管理、发布管理等**方面的管理。

软件配置管理的目标是确保软件系统的可控性、可重现性和可追溯性，以提高软件开发过程的效率和质量。主要功能包括：

1. ```版本控制```：管理和控制软件系统不同版本的源代码、文档和相关文件。
2. ```变更管理```：记录和跟踪对软件系统进行的变更，包括需求变更、缺陷修复、功能增加等。
3. ```构建管理```：管理和自动化构建过程，确保可重现、可靠的构建结果。
4. ```发布管理```：跟踪、计划和控制软件系统的发布过程。
5. ```配置审计```：对软件配置进行审计，确保符合规定的配置管理策略和标准。

通过软件配置管理的实施，团队可以更好地控制和跟踪软件开发过程中的各种变更，降低配置错误和不一致的风险，提高软件开发的质量和可靠性。

## 过程的适应性调整

不同的项目所采用的项目过程可能有很大的不同，这些**不同**主要体现在以下方面：

- 活动、动作和任务的总体流程以及相互依赖关系。
- 在每一个框架活动中，动作和任务细化的程度。
- 工作产品的定义和要求的程度。
- 质量保证活动应用的方式。
- 项目跟踪和控制活动应用的方式。
- 过程描述的详细程度和严谨程度。
- 客户和利益相关者对项目的参与程度。
- 软件团队所赋予的自主权。
- 队伍组织和角色的明确程度。