# Agent调研
## 什么是Agent? 
Agent的核心决策逻辑: 让LLM根据动态变化的环境信息选择执行具体的行动或者对结果作出判断，并影响环境，通过多轮迭代重复执行上述步骤，直到完成目标。

精简的决策过程: P（感知）→ P（规划）→ A（行动）
感知（Perception）是指Agent从环境中收集信息并从中提取相关知识的能力。
规划（Planning）是指Agent为了某一目标而作出的决策过程。
行动（Action）是指基于环境和规划做出的动作。

