# RelayNet Vision

> This is the official vision and positioning of the RelayNet project.
> 本文档是 RelayNet 项目的官方愿景与定位说明。

**A neutral protocol for responsibility handoff in cross-organization logistics**  
**跨组织物流责任接力的中立协议与基础设施**

---

## English

### What is RelayNet?

RelayNet is a **protocol-first platform** designed to model and govern  
**responsibility handoff across organizations** in logistics workflows.

It does not focus on transportation, dispatching, or execution.  
Instead, RelayNet addresses a long-standing structural gap:

> **How responsibility is clearly transferred, validated, and audited  
> when multiple organizations are involved.**

---

### The problem we focus on

In real-world logistics:

- Goods move across many organizations  
- Systems are fragmented  
- Contracts and responsibilities are often implicit  
- Accountability is usually reconstructed *after* problems occur  

Most existing systems optimize operations,  
but very few treat **responsibility itself** as a first-class concept.

RelayNet is built to fill this gap.

---

### Core idea

RelayNet turns responsibility handoff from an implicit assumption  
into an **explicit, auditable protocol object**.

At the core of RelayNet are a small set of neutral abstractions:

- **Relay Task** – a complete cross-organization responsibility chain  
- **Relay Stage** – a bounded responsibility interval owned by one party  
- **State Transition** – formal rules for responsibility transfer  
- **Auditable Event** – immutable records of responsibility change  

These abstractions are **industry-agnostic**,  
independent of transport mode, business model, or system architecture.

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
  Defines responsibility models, state machines, and audit semantics  
  as a transparent, verifiable protocol

- **SDKs**  
  Provide integration tools without embedding rules or decisions

- **Enterprise distributions**  
  Offer deployment, compliance, and industry extensions  
  without altering the core protocol

This separation ensures that:

> **Rules remain neutral,  
> integration remains flexible,  
> and commercialization remains controlled.**

---

### How RelayNet is used

In practice, RelayNet is rarely a standalone system.

It is typically:

- Embedded into existing logistics platforms  
- Used as a responsibility and audit backbone  
- Referenced by contracts, compliance, or dispute resolution  
- Deployed as part of private or consortium infrastructure  

RelayNet is most valuable when it is **invisible but indispensable**.

---

### Project direction

RelayNet is evolving as a **long-term infrastructure project**, not a product feature.

The roadmap prioritizes:

1. Clear abstractions and protocol semantics  
2. Stable, auditable responsibility models  
3. Interoperability across organizations and systems  

Functionality follows **after** correctness and clarity.

---

### Our vision

> **To make responsibility handoff in logistics  
> as explicit, verifiable, and interoperable  
> as data exchange is today.**

RelayNet aims to become a shared foundation  
for trust, accountability, and collaboration  
across organizational boundaries.

---

## 中文

### RelayNet 是什么？

RelayNet 是一个面向 **跨组织物流协作场景** 的  
**协议优先（protocol-first）责任接力平台与基础设施**。

它关注的不是运输、调度或执行过程本身，  
而是一个长期被忽视的结构性问题：

> **当多个组织参与时，  
> 责任如何被清晰地交接、验证与审计。**

---

### 我们关注的问题

在真实的物流体系中：

- 货物在多个组织之间流转  
- 系统彼此割裂  
- 合同与责任往往是隐含的  
- 责任通常只能在问题发生后追溯  

现有系统大多优化的是“操作效率”，  
而极少将 **责任本身** 作为一等对象来建模。

RelayNet 正是为填补这一空白而设计。

---

### 核心思想

RelayNet 将“责任接力”  
从隐含假设转化为 **显式、可审计的协议对象**。

其核心由一组中立抽象构成：

- **接力任务（Relay Task）**：完整的跨组织责任链  
- **接力阶段（Relay Stage）**：由某一方承担责任的边界区间  
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
  作为透明、可验证的协议基础

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

### RelayNet 如何被使用

在实践中，RelayNet 很少作为一个独立系统存在。

它通常：

- 嵌入现有物流或协作系统  
- 作为责任与审计的底层能力  
- 被合同、合规或争议处理所引用  
- 部署在私有或联盟基础设施中  

RelayNet 最有价值的状态是：  
**不可或缺，但并不显眼。**

---

### 项目方向

RelayNet 被设计为一个 **长期基础设施项目**，而非短期产品功能。

其演进优先级始终是：

1. 清晰、稳定的抽象与协议语义  
2. 可验证、可审计的责任模型  
3. 跨组织、跨系统的互操作性  

功能实现永远服从于 **正确性与清晰性**。

---

### 愿景

> **让物流中的责任接力，  
> 像今天的数据交换一样，  
> 清晰、可验证、可互操作。**

RelayNet 希望成为  
跨组织协作中 **信任、责任与合规** 的共同基础。

---

© 2026 RelayNet  
Protocol before product. Rules before implementation.
