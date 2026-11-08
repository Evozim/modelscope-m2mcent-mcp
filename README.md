# ModelScope (魔搭社区) M2MCent MCP Gateway 集成指南 (v2.1.0)

[![Vouch Protocol Grade A](https://img.shields.io/badge/Vouch_Trust_Index-Grade_A_(100%2F100)-00ff88?style=flat-square)](https://vouch-protocol.com/agent-trust-index/)
[![Base Mainnet](https://img.shields.io/badge/Settlement-Base_Mainnet_(USDC)-0052FF?style=flat-square)](https://basescan.org)
[![Post-Quantum Ready](https://img.shields.io/badge/Post--Quantum-ML--DSA--65_(FIPS_204)-purple?style=flat-square)](https://csrc.nist.gov/pubs/fips/204/final)
[![Compute SLA](https://img.shields.io/badge/Compute_SLA-%3C250ms_Deterministic-brightgreen?style=flat-square)](https://m2mcent.com)

## 🇨🇳 中文说明 (Chinese Guide)

**M2MCent** 是专为自主 AI 智能体（AI Agents）打造的高性能确定性微服务与 MCP（Model Context Protocol）网络，基于 **Base Mainnet (`eip155:8453`)** 链上 **x402 V2 (EIP-3009)** 协议运行，已通过 **Vouch Protocol Grade A (100/100)** 信任认证并具备抗量子密码学（FIPS 204 ML-DSA-65）支持。

本指南帮助开发者在 **ModelScope (魔搭社区)**、**Qwen (通义千问)** 和 **Dify/FastGPT** 中一键接入 M2MCent 的 **1,057 个确定性内存引擎微服务**（引擎计算延迟 `<250ms`，单次调用 `$0.010`–`$0.250` USDC）。

### 🚀 快速接入 (Quickstart)

```json
{
  "mcpServers": {
    "m2mcent-gateway": {
      "url": "https://api.m2mcent.com/sse",
      "type": "sse",
      "description": "M2MCent 1,057 节点确定性 AI 智能体微服务网络 (<250ms SLA)"
    }
  }
}
```

---

## 🌐 English Guide

- **SSE Endpoint:** `https://api.m2mcent.com/sse`
- **Catalog Endpoint:** `https://api.m2mcent.com/api/v1/tools`
- **Free Dry-Run Preview:** `POST https://api.m2mcent.com/{slug}/api/preview`
- **Paid Execution (x402 V2):** `POST https://api.m2mcent.com/{slug}/api/process`
- **Smart Contract Escrow (Base Mainnet):** `0x5d47070A36A37DAf417e64FF27a1e5B3F1c84efa`
- **Institutional Treasury Safe:** `0x8aaBAB75bE8825d0f5D514a9a5cBa04B7bF84920`
- **Python SDKs (PyPI v1.0.3):** `pip install m2mcent-sdk m2mcent-langchain-x402 crewai-plugin-x402 m2mcent-llamaindex-x402 autogen-plugin-x402 m2mcent-huggingface-x402`
