### EXTRA：
    - 轻量，可针对业务定制化
    - 基于用户反馈和学习能力（LTM and retrival）
    - 知识库召回

[agent](agent) - 思考框架（planning）
 - boss：根据Agents的职责，对用户指令进行拆解，计划
 - 原先的boss降级为：业务判断agent
 - 原先的Expert考虑降级为：功能性Agent

[library](library) - 图书馆
 - 知识仓库

*[memory](memory) - 记忆
 - Agent所扮演角色的LTM和STM。

[actions](actions) - 想法，实现路径
 - 动作，要做什么？为此需要执行的对应动作。

[helper](helper) 工具
 - 实现某些动作所需要的工具

[brains](brains)
 - 不同大脑，也就是LLM

[controllers](..%2Fcontrollers)
 - 控制层，凌驾于Agent之上可对业务进行强把控
 - 所谓强把控:可以基于简云系统的workflow配置,前期使用预置workflow