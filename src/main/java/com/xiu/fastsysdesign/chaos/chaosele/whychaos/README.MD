# 为什么需要混沌工程

## 什么是混沌工程

	在一个复杂的分布式系统中，会发生各种无法预料的突发时间，任何一次处理不好就可能导致业务停滞等各种异常行为。
这单靠人力并不能完全阻止这些故障发生，而是应该致力于这些异常行为被触发之前。尽快的识别出系统中脆弱和易出现
故障的环节。只有当提前识别风险时，就可以有针对性的对系统进行加固，防范，从而避免带来的严重后果,这样才能不断
打造更具弹性系统,进而建立对运行高可用分布式系统的信心.

混沌工程就是这样一种通过在系统基础设施上进行实验,主动找出系统中脆弱环节的科学方法.通过设计和执行一系列的实验,帮助
我们发现系统中潜在的脆弱环节

## 混沌工程和测试的区别

混沌工程,故障注入,和故障测试在侧重点和工具集使用上有一些重叠.很多混沌工程试验的研究对象都是基于故障注入引进的