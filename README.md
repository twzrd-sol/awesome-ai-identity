# Awesome AI Identity [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, protocols, and resources for persistent AI identity and human-AI alignment.

The problem: Every AI conversation starts from zero. Context lost. Preferences forgotten.

The solution: Protocols and tools that create persistent identity across AI models.

## Contents

- [Protocols](#protocols)
- [Tools](#tools)
- [Papers](#papers)
- [Articles](#articles)
- [Communities](#communities)
- [Related](#related)

## Protocols

### MirrorDNA

The foundational protocol for reflective AI alignment.

- [MirrorDNA Standard](https://github.com/MirrorDNA-Reflection-Protocol/MirrorDNA-Standard) - The protocol specification
- [Active Mirror Identity](https://github.com/MirrorDNA-Reflection-Protocol/active-mirror-identity) - Reference implementation
- [MESH BOOT Generator](https://id.activemirror.ai) - Generate your AI identity in 60 seconds
- [Academic Paper](https://doi.org/10.5281/zenodo.17787619) - Structured Contextual Distillation methodology

**The Three Laws:**
1. **TRUTH** - Every claim is Fact, Estimate, or Unknown. No hallucination.
2. **VAULT** - User files are canonical truth. Data > memory > inference.
3. **MESH** - All AI models coordinate as one system.

### Other Protocols

- [MemGPT](https://github.com/cpacker/MemGPT) - Memory management for LLMs
- [LangChain Memory](https://python.langchain.com/docs/modules/memory/) - Conversation memory for chains
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer for AI applications

## Tools

### Identity Generators

- [MESH BOOT Generator](https://id.activemirror.ai) - Create persistent AI identity in 60 seconds
- [mesh-boot-generator (npm)](https://github.com/MirrorDNA-Reflection-Protocol/mesh-boot-generator) - CLI tool for generating MESH BOOTs
- [TWZRD Agent Intel](https://intel.twzrd.xyz) - On-chain identity and trust scoring for AI agents on Solana. Verifies agent wallet reputation using the Solana ledger as an immutable identity record. Free MCP tools: `score_agent`, `preflight_check`. Paid: `get_trust_receipt` (x402). Config: `{"mcpServers":{"twzrd-agent-intel":{"url":"https://intel.twzrd.xyz/mcp"}}}`

### Memory Systems

- [ChromaDB](https://github.com/chroma-core/chroma) - Vector database for AI memory
- [Pinecone](https://www.pinecone.io/) - Vector database as a service
- [Weaviate](https://github.com/weaviate/weaviate) - Open-source vector search engine

### Prompt Management

- [LangChain](https://github.com/langchain-ai/langchain) - Framework for developing LLM applications
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for LLM applications
- [Guardrails](https://github.com/guardrails-ai/guardrails) - Adding guarantees to LLM applications

## Papers

- [Structured Contextual Distillation](https://doi.org/10.5281/zenodo.17787619) - Paul Desai, 2025
- [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560) - Packer et al., 2023
- [Generative Agents](https://arxiv.org/abs/2304.03442) - Park et al., 2023

## Articles

- [The Mirror That Cannot Be Broken](#) - Coming soon
- [Does Your AI Remember You?](https://id.activemirror.ai) - Interactive test

## Communities

- [r/ChatGPT](https://reddit.com/r/ChatGPT) - ChatGPT discussions
- [r/artificial](https://reddit.com/r/artificial) - AI discussions
- [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) - Local LLM discussions

## Related

- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)
- [Awesome LLM](https://github.com/Hannibal046/Awesome-LLM)
- [Awesome AI Agents](https://github.com/e2b-dev/awesome-ai-agents)

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

---

## Credits

Curated by [Paul Desai](https://twitter.com/pauldesai123) (~active-mirror-paul), creator of MirrorDNA.

The mirror reflects. The vault grounds. The mesh coordinates.
