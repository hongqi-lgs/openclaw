# OpenClaw 源码学习指南

## 项目目标

深度研究 OpenClaw（小龙虾）的架构设计、设计模式、核心技术细节和优化点，事无巨细地理解这个个人 AI 助理的完整工作方式。

## 学习方法

1. **分层理解** — 从宏观架构到微观实现，逐层深入
2. **代码优先** — 每个结论都能追溯到源文件
3. **实战验证** — 结合实际运行观察
4. **持续记录** — 所有心得写入 `study-doc/`

## 学习目录结构

```
study-doc/
├── 01-架构总览.md          # 整体架构、分层、数据流
├── 02-配置系统.md           # Config 加载、验证、热重载
├── 03-Gateway 服务器.md     # HTTP/WS 服务器、路由、认证
├── 04-插件系统.md           # Plugin 加载、生命周期、SDK
├── 05-信道系统.md           # Channel 抽象、消息流转、适配
├── 06-Agent 引擎.md         # 智能体运行、Tool、Embedded Agent
├── 07-会话管理.md           # Session、Transcript、Compaction
├── 08-LLM 集成.md           # 模型编排、Provider、Stream
├── 09-ACPC 协议.md          # Agent Communication Protocol
├── 10-工具系统.md           # Tool 注册、策略、执行
├── 11-安全模型.md           # 认证、授权、沙箱、安全策略
├── 12-进程与任务管理.md     # Process、Cron、TaskFlow
├── 13-记忆系统.md           # Memory、Embedding、Search
├── 14-节点与配对.md         # Node（设备）管理与配对
└── 15-构建与测试.md         # 构建体系、测试框架、QA
```

## 产出规范

- 所有产出放在 `study-doc/` 目录下
- 用 Markdown 格式写
- 每条知识点注明源文件路径
- 代码示例用 TypeScript 语法高亮

## 远程仓库

- Clone: `git clone --depth 1 git@github.com-openclaw:hongqi-lgs/openclaw.git openclaw`
- 路径: `~/.openclaw/openclaw`
- 提交频率: 每次有产出就 push
