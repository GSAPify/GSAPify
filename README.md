# Akhil Singh

AI Engineering Lead at [Pattern](https://www.pattern.com). Pune.

I work on AI automation and infrastructure for ecommerce operations: compliance screening platforms, RAG architectures, marketplace automation pipelines, and the AWS, Snowflake, and Terraform infrastructure underneath them. Most of it lives in private repos. Happy to walk through any of the architecture.

## Public

**[ohlcv-validator](https://github.com/GSAPify/ohlcv-validator)** · C++20

Low-latency validator, feed handler, and L2 order book for live market data. Zero heap allocations on the hot path, ~6 ns per record, ~167M records/sec on a single core. Lock-free SPSC pipeline, A/B multicast feed handler, snapshot recovery. Latency tails measured with rdtscp: p50 20 ns, p99 30 ns on x86. Every correctness claim has a test, every performance claim has a reproducible benchmark.

**[bird_mach](https://github.com/GSAPify/bird_mach)** · Python

Audio intelligence platform. Real-time WebSocket streaming, fingerprinting with Chromaprint and constellation matching, plugin-based DSP effects chain, spectral and harmonic analysis with UMAP.

**[IsacxAkhil](https://github.com/GSAPify/IsacxAkhil)** · Python, Rust

Robotics perception in Isaac Sim. Keypoint-based 6-DoF tracking and pose estimation, working toward control-aware ML and simulation-driven development.

## Stack

```
Languages     Python, C++20, SQL, TypeScript, Rust (learning)
Systems       Lock-free SPSC queues, cache-aware layout, mmap I/O, zero-alloc hot paths
ML            PyTorch, LangChain, RAG pipelines, pgvector, Apache AGE
Backend       FastAPI, Node.js
Infra         AWS (ECS, Lambda, Textract, Cognito), Terraform, Snowflake, Postgres
Automation    n8n, workflow orchestration
```

## Now

- EDITH, a local-first voice assistant. Wake-word daemon, mic preflight, tool routing
- Lock-free structures and cache-aware layouts in modern C++
- Graph-agentic RAG on Postgres with Apache AGE and pgvector
- Kalman filtering literature
- Rust

---

National cross-country mountain biking champion, 2021.

[LinkedIn](https://www.linkedin.com/in/akhil-singh-/) · [akhilshreds1010@gmail.com](mailto:akhilshreds1010@gmail.com)

[![GitHub Streak](https://streak-stats.demolab.com/?user=GSAPify&theme=dark&hide_border=true&background=0D1117&ring=FFFFFF&fire=FFFFFF&currStreakLabel=FFFFFF)](https://github.com/GSAPify)
