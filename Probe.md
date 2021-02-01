# Probe
<!-- 合适的项目名称（非暴力、色情、歧视，符合相关国家法规规定）-->
https://github.com/SamYuan1990/Probe
<!-- 如果项目主要的托管平台不是Github，需要在Github.com建立mirror镜像，并提供链接 -->
<!-- 项目内容的要求
- 开源许可证License：Apache 2.0或兼容协议
- 完整的Readme
- 贡献流程Contribution guideline
- 持续集成（文档类项目除外）
- commit需要有sign-off
-->

## 简介
<!-- 请用不多于50字的简介来描述你的项目 -->
根据[性能测试白皮书](https://www.hyperledger.org/learn/publications/blockchain-performance-metrics), Probe是一个面向Hyperledger Fabric维护者，用户，研究者的web UI的应用程序，旨在提供控制被测网络（SUT）并协调压力生成工具于观察工具，来针对性的观察Fabric出块参数对于Fabric网络性能的影响。

## 目的
<!-- 相比于其他项目，这个项目不同之处在哪？ -->
<!-- 解决了什么痛点？-->
<!-- 是否开辟了具有前瞻性和预见性的领域？或者有清晰明确的产出物？ -->
Probe是在TWGC performance work group的交流中， 解决我们对于“如何配置出块参数来达到最大tps？”这一痛点而创立并实现的项目。因此，本项目旨在开辟配置参数与性能相关关系研究的领域的测试工具。

## 路线图和计划
version | define| feature
---|---|---
0.0.3 | back end refactor | i18n & minifab
1.0.0 | fix up bugs after 0.0.3 | 
1.0.1 | furhter network supports | supports caliper, cello ? and other platform

## 项目的活跃度参考
<!-- 请尽可能提供项目被引用，参考的链接 -->
<!-- 在评审的过程中，也会参考其他的Github硬性活跃度指标 -->
立项于Oct 14, 2020 至今半年3个fork（还有韩国朋友），另外感谢来自复旦大学的同学开issue的方式进行反馈。
另外文档：https://github.com/SamYuan1990/Probe/blob/main/doc/HowToConfigFabricParameters_ZH.md