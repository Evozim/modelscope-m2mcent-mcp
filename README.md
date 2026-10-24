# ModelScope (魔搭社区) M2MCent MCP Gateway 集成指南

[![Vouch Protocol Grade A](https://img.shields.io/badge/Vouch_Trust_Index-Grade_A_(100%2F100)-00ff88?style=flat-square)](https://vouch-protocol.com/agent-trust-index/)
[![Base Mainnet](https://img.shields.io/badge/Settlement-Base_Mainnet_(USDC)-0052FF?style=flat-square)](https://basescan.org)
[![Post-Quantum Ready](https://img.shields.io/badge/Post--Quantum-ML--DSA--65_(FIPS_204)-purple?style=flat-square)](https://csrc.nist.gov/pubs/fips/204/final)

[English Version Below]

## 🇨🇳 中文说明 (Chinese Guide)

**M2MCent** 是首个专为自主人工智能智能体（AI Agents）打造的去中心化微服务与 MCP（Model Context Protocol）网络，基于 **Base Mainnet** 链上 **x402 V2** 协议运行，已通过 **Vouch Protocol Grade A (100/100)** 信任认证并具备抗量子密码学（FIPS 204 ML-DSA-65）支持。

本指南帮助中国及亚洲的开发者在 **ModelScope (魔搭社区)**、**Qwen (通义千问)** 和 **Dify/FastGPT** 中一键接入 M2MCent 的 **1,062 个专业 AI 微服务**（包含 896 个旗舰确定性内存引擎）。

### 🚀 快速接入 (Quickstart)

在你的 MCP 配置文件（如 `mcpServers.json` 或 Claude/Cursor/Qwen Agent 配置）中添加：

```json
{
  "mcpServers": {
    "m2mcent-gateway": {
      "url": "https://api.m2mcent.com/sse",
      "type": "sse",
      "description": "M2MCent 1,062 节点企业级 AI 智能体微服务网络"
    }
  }
}
```

### 🛠️ 核心功能与领域
1. **金融与智能合约 (DeFi & Smart Contracts):** 信用风险评估、Uniswap 流动性分析、智能合约形式化验证、基于 Coinbase 实时 50 根 K 线的 MACD/RSI 量化引擎。
2. **网络安全与抗量子隐私 (Security & Cryptography):** EIP-5564 隐身地址、EIP-712 结构化签名、ZK-SNARK 验证、漏洞扫描。
3. **生物医疗与医药 (Bioinformatics & Pharma):** 基因变异分析、分子结构解析、药物动力学。
4. **多媒体与 3D 生成 (3D & Spatial Audio):** 3D 网格优化、实时字幕转译、语音克隆分析。

---

## 🌐 English Guide

### Overview
**M2MCent** is a high-throughput monolithic Model Context Protocol (MCP) gateway aggregating **1,062 autonomous AI agent micro-services** (896 Flagship deterministic in-memory engines) monetized via the **x402 V2 protocol** on **Base Mainnet**.

### Integration
Point your ModelScope agent or MCP client to the unified SSE endpoint:
- **SSE URL:** `https://api.m2mcent.com/sse`
- **Catalog Endpoint:** `https://api.m2mcent.com/api/v1/tools`
- **Smart Contract Escrow:** `0x5d47070A36A37DAf417e64FF27a1e5B3F1c84efa` (Base Mainnet)
- **Institutional Treasury Safe:** `0x8aaBAB75bE8825d0f5D514a9a5cBa04B7bF84920`
- **Trust Certification:** Vouch Protocol Grade A (100/100)
