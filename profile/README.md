# RelayNet

**This is the official vision and positioning of the RelayNet project.**
**本文档是 RelayNet 项目的官方愿景与定位说明。**


**A protocol-first infrastructure for responsibility handoff in cross-organization logistics**  
**跨组织物流责任接力的中立协议与基础设施**

- 🌐 Project site: https://relaynet.dev
- 📜 Project Constitution:  
  https://github.com/relaynet-org/relaynet-core/blob/main/docs/PROJECT_CONSTITUTION.md

---

## English

### What is RelayNet?

RelayNet is a **protocol-first infrastructure project** that defines how  
**responsibility is explicitly handed off, validated, and audited**  
across organizations in logistics workflows.

RelayNet does not focus on transportation, dispatching, or execution.  
It focuses on a structural gap that existing systems rarely address:

> **Who is responsible, for what, at which stage — and how that responsibility is transferred.**

---

### The problem

In real-world logistics environments:

- Goods move across multiple organizations  
- Systems are fragmented and loosely coupled  
- Contracts and responsibilities are often implicit  
- Accountability is usually reconstructed *after* incidents occur  

Most systems optimize operational efficiency.  
Very few model **responsibility itself** as a first-class concept.

RelayNet is designed to fill this gap.

---

### Core idea

RelayNet models responsibility handoff as an **explicit protocol object**.

Core abstractions include:

- **Relay Task** – a complete cross-organization responsibility chain  
- **Relay Stage** – a bounded responsibility interval owned by one party  
- **State Transition** – formal rules governing responsibility transfer  
- **Auditable Event** – immutable records of responsibility change  

These abstractions are **industry-agnostic** and independent of  
transport mode, business model, or system architecture.

---

### What RelayNet is not

RelayNet is intentionally **not**:

- A TMS / WMS / OMS  
- A dispatch or capacity marketplace  
- A SaaS business application  
- A replacement for existing logistics systems  

RelayNet does not compete with operational systems.  
It provides a **neutral responsibility layer between them**.

---

### Architecture philosophy

RelayNet follows a **protocol-first, open-core** architecture:

- **Core**  
  Protocol definitions, state machines, and audit semantics
- **SDKs**  
  Integration tools without embedded rules or decisions
- **Enterprise distributions**  
  Deployment, compliance, and industry extensions  
  without altering core protocol semantics

This separation ensures:

> **Rules remain neutral.  
> Integration remains flexible.  
> Commercialization remains controlled.**

---

### Project direction

RelayNet is a **long-term infrastructure project**, not a product feature.

Its evolution prioritizes:

1. Clear abstractions and protocol semantics  
2. Stable and auditable responsibility models  
3. Interoperability across organizations and systems  

Implementation follows **after** correctness and clarity.

---

## 中文

### RelayNet 是什么？

RelayNet 是一个 **协议优先（protocol-first）的基础设施项目**，  
用于定义跨组织物流协作中  
**责任如何被显式地交接、验证与审计**。

RelayNet 不关注运输、调度或执行过程本身，  
而是聚焦一个长期存在却被忽视的结构性问题：

> **在多方参与的情况下，  
> 谁在什么阶段对什么负责，以及责任如何被合法地转移。**

---

### 问题背景

在真实的物流体系中：

- 货物在多个组织之间流转  
- 系统之间高度割裂  
- 合同与责任往往是隐含的  
- 责任通常只能在问题发生后被追溯  

现有系统大多优化的是“操作效率”，  
而极少将 **责任本身** 作为一等对象来建模。

RelayNet 正是为填补这一空白而设计。

---

### 核心思想

RelayNet 将“责任接力”  
从隐含假设转化为 **显式、可审计的协议对象**。

其核心抽象包括：

- **接力任务（Relay Task）**：完整的跨组织责任链  
- **接力阶段（Relay Stage）**：某一参与方承担责任的边界区间  
- **状态转移（State Transition）**：责任合法迁移的规则  
- **可审计事件（Auditable Event）**：责任变化的事实记录  

这些抽象 **不依赖具体行业、运输方式或业务系统**。

---

### RelayNet 不是什么

RelayNet 明确 **不是**：

- TMS / WMS / OMS  
- 运力撮合或调度平台  
- SaaS 业务系统  
- 现有物流系统的替代品  

RelayNet 不与操作系统竞争，  
而是在系统之间提供一个 **中立的责任协议层**。

---

### 架构理念

RelayNet 采用 **协议优先、开源内核（open-core）** 的架构理念：

- **Core（内核）**  
  定义责任模型、状态机与审计语义
- **SDK（接入工具）**  
  提供集成能力，但不内嵌规则或决策
- **企业发行版**  
  提供部署、合规与行业扩展  
  但不改变核心协议语义

这种分层确保：

> **规则保持中立，  
> 接入保持灵活，  
> 商业保持可控。**

---

### 愿景

> **让物流中的责任接力，  
> 像今天的数据交换一样，  
> 清晰、可验证、可互操作。**

RelayNet 希望成为  
跨组织协作中 **信任、责任与合规** 的共同基础。

---

© 2026 RelayNet  
**Protocol before product. Rules before implementation.**
