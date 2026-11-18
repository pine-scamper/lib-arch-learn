# 01 - spdlog 源码研究

## 项目定位

研究一个现代 C++ 日志库如何拆分 Logger、Sink、Formatter、Registry 和异步线程池；重点关注组件组合、扩展接口、线程安全及资源生命周期。

## 本次研究范围

- [ ] 同步日志调用链
- [ ] Logger 与多个 Sink 的组合关系
- [ ] Formatter 与 Sink 的职责边界
- [ ] Registry / 默认 Logger 的管理
- [ ] 异步日志队列、线程池及溢出策略
- [ ] 自定义 Sink 实验
- [ ] mini-logger 独立设计

## 项目版本

- 上游仓库：https://github.com/gabime/spdlog
- Tag/Release：待填写
- Commit：待填写
- 编译器/版本：待填写
- 构建选项：待填写
- OS/架构：待填写

## 阅读入口

- 范围定义：`00-scope.md`
- 架构分析：`01-architecture/architecture.md`
- 核心调用链：`02-call-chains/`
- 设计模式：`03-design-patterns/`
- 关键模块：`04-deep-dives/`
- 动手实验：`05-experiments/`
- 独立设计：`06-design-reconstruction/`
- 最终复盘：`07-synthesis.md`
- 参考资料：`references.md`
