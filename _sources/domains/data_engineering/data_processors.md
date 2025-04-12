# 数据处理器

## 概述

文档、测试、代码模块一一对应。

组成：
- 文档：说明模块功能和设计思路，并明确验收标准和对应的测试设计思路。
- 测试：列举所有的测试可能，并使用单元测试实现。

流程：
1. 文档驱动开发：先写文档、再写测试和代码。文档要结合需求和开发思路，确保开发的技术和验收结果的非技术都可以理解。
2. 测试驱动开发：遵循红-绿-重构的流程，先根据规范的测试管理方式列举各种可能性，然后实现和重构。


## 模块划分

代码文件夹：
- src/__main__模块
- src/processors模块
- src/repositories模块
- src/models模块

文档文件夹：
- docs/README模块，对应mian模块
- docs/processors模块
- etc

单元测试文件夹：

- tests/test_main模块。
- test/test_processsors模块。
- etc

集成测试模块为：
- integrated_tests/test_main模块
- etc
