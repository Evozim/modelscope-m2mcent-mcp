# ModelScope (魔搭社区) M2MCent MCP Gateway 集成指南

[English Version Below]

## 🇨🇳 中文说明 (Chinese Guide)

**M2MCent** 是首个专为自主人工智能智能体（AI Agents）打造的去中心化微服务与 MCP（Model Context Protocol）网络，基于 **Base Mainnet** 链上 **x402 V2** 协议运行。

本指南帮助中国及亚洲的开发者在 **ModelScope (魔搭社区)**、**Qwen (通义千问)** 和 **Dify/FastGPT** 中一键接入 M2MCent 的 **1,005 个专业 AI 微服务**。

### 🚀 快速接入 (Quickstart)

在你的 MCP 配置文件（如 `mcpServers.json` 或 Claude/Cursor/Qwen Agent 配置）中添加：

```json
{
  "mcpServers": {
    "m2mcent-gateway": {
      "url": "https://api.m2mcent.com/sse",
      "type": "sse",
      "description": "M2MCent 1,005 节点企业级 AI 智能体微服务网络"
    }
  }
}
```

### 🛠️ 核心功能与领域
1. **金融与智能合约 (DeFi & Smart Contracts):** 信用风险评估、Uniswap 流动性分析、智能合约形式化验证。
2. **网络安全与零知识证明 (Zero-Knowledge & Security):** ZK-SNARK 验证、漏洞扫描、反钓鱼检测。
3. **生物医疗与医药 (Bioinformatics & Pharma):** 基因变异分析、分子结构解析、药物动力学。
4. **多媒体与 3D 生成 (3D & Spatial Audio):** 3D 网格优化、实时字幕转译、语音克隆分析。

---

## 🌐 English Guide

### Overview
**M2MCent** is a high-throughput monolithic Model Context Protocol (MCP) gateway aggregating **1,005 autonomous AI agent micro-services** monetized via the **x402 V2 protocol** on **Base Mainnet**.

### Integration
Point your ModelScope agent or MCP client to the unified SSE endpoint:
- **SSE URL:** `https://api.m2mcent.com/sse`
- **Catalog Endpoint:** `https://api.m2mcent.com/api/v1/tools`
- **Smart Contract Escrow:** `0xDb48F51A2de8F4a80CD1d0BAdcd18E847734A74a` (Base Mainnet)
