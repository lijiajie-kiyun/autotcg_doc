# 凯云自动化测试用例设计平台（AutoTCG OnLine）

### 简介
 AutoTCG OnLine是凯云公司推出的在线自动化测试用例设计平台，通过在线创建可视化测试模型，自动生成测试用例
 - AutoTCG采用先进的数学算法，可实现全面科学的测试覆盖
 - AutoTCG适用于嵌入式软件测试、web应用测试、移动app测试、桌面软件测试等多种自动化测试场景

### 主要功能

#### 可视化建模
- 采用标准的BPMN2.0符号，可视化构建测试模型
- 简单便捷的模型设计器，快速构建测试模型
- 实时的模型自动检查功能，随时发现问题
- 支持子模型多层嵌套，分解复杂的业务逻辑

#### 输入参数设计
- 分步骤配置输入参数，方便人工分析
- 输入参数约束设置支持计算表达式，适用范围更广
- 自动识别参数类型，使用更简单
- 自动分析输入参数，及早定位设计问题

#### 自动生成测试用例
- 采用路径深度覆盖算法，确保执行步骤的全面覆盖
- 采用组合配对算法，确保输入参数组合的科学覆盖
- 采用路径约减算法，确保测试用例的最优覆盖
- 自动求解约束，保证每条测试用例的有效性

#### 执行代码输出
- 自动生成python、lua、javascript、c#、c++等多种程序代码
- 支持代码生成插件定制
- 自动生成测试用例执行列表
- 一键打包下载

#### 文档输出
- 一键生成测试用例说明文档
- 支持多种输出格式
- 支持输出格式定制


### AutoTCG系列产品
AutoTCG是凯云公司自主研发的自动化测试用例生成引擎，集成有AutoTCG引擎的产品包括：
- AutoTCG OnLine：在线自动化测试用例设计平台
- AutoTCG专业版：将AutoTCG引擎与Selenium集成在一起的自动化测试工具，主要用于Web应用测试
- ETestLite：将AutoTCG引擎与ETest核心引擎集成在一起的自动化测试工具，主要用于嵌入式软件测试
- AutoTCG定制版：根据不同用户需求，可进行量身定制的自动化测试产品
