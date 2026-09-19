# 搜索工具配置（CPU/OS 底层领域）

## 工具选择
- **首选**：Claude Code 内置 WebSearch（零配置、免费，直接可用）
- **可选升级**：Tavily Search API（结果更适合 AI 处理，但需要付费 API key，暂不配）

## 权威来源白名单（只认这些，不用来源不明的博客/论坛/问答）

### 指令集架构官方规范
- RISC-V 规范：riscv.org（非特权规范 / 特权规范）
- ARM 架构参考手册（ARM ARM）
- x86/AMD 软件开发手册（Intel SDM / AMD APM）

### 操作系统
- Linux 内核源码与文档：kernel.org
- POSIX 规范
- 各操作系统官方文档

### 学术来源
- 体系结构顶会：ISCA、MICRO、HPCA、ASPLOS
- 操作系统顶会：OSDI、SOSP
- 编译/编程语言顶会：PLDI、CGO
- 论文预印本：arXiv

### 权威教材（作为概念定义来源）
- 《深入理解计算机系统》(CSAPP)
- 《计算机组成与设计》(Patterson & Hennessy)
- 《操作系统概念》(Silberschatz)
- 《计算机体系结构：量化研究方法》(Hennessy & Patterson)

## 使用规范
1. 检索时优先命中白名单来源
2. 命中的资料记录：标题、URL、日期、章节/条款
3. 白名单之外的来源（如个人博客、论坛、问答）不采用为结论依据
