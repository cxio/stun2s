# stun2s NAT 探测和打洞服务

这是对 `stun2` 项目的一个服务端实现，提供基于新的 STUN2 协议的 NAT 类型和存活期探测，以及 UDP 打洞协助功能。


## 功能

- 提供节点公网地址查询（STUN:Addr）。
- 支持节点 NAT 类型探测（STUN:Cone）。
- 支持节点 NAT 存活期探测（STUN:Live）。
- 协助节点 UDP 打洞（STUN:Punchs），随机节点，多个。
- 协助节点 UDP 打洞（STUN:PunchTo，定向打洞）。


## 使用
