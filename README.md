# 🌀 Hey, I'm Arpan Das

Backend Software Engineer · 4+ years · Node.js & AWS · backends that move millions of events a day without flinching.

I build the unglamorous plumbing that keeps things running: messaging pipelines, caching layers, queues that never lose a job — spirals that loop forever but never collapse. Outside of production code, I cook, I read about systems and psychology, and I'm slowly collecting passport stamps.

**[Portfolio](https://arpandas-eight.vercel.app/) · [Resume](https://arpandas-eight.vercel.app/assets/arpan_das_resume.pdf) · [Writing](https://adasarpan.hashnode.dev/) · [LinkedIn](https://www.linkedin.com/in/arpandas-adasarpan/)**

---

## What I've actually shipped

**Guni SMS** — Senior Backend Engineer (Feb 2022 – present)
- Built a multi-stage AWS Lambda pipeline (SQS, S3, Redis, MongoDB) processing **1M SMS/MMS per hour**
- Designed Redis-backed auth caching with Lua scripts + Pub/Sub invalidation — cut MongoDB auth reads by **90%**
- Built a multi-provider routing layer with automatic fallback — cut SMS costs **33%**, MMS costs **50%**
- Led blue-green deployments on AWS ELB for zero-downtime rollouts

**FluidFit.ai** — Senior Software Engineer, Contract (Dec 2025 – Feb 2026)
- Architected multimodal AI media pipelines across Gemini, Veo, and Imagen with provider fallback
- Shipped image-processing services (Sharp/Jimp) and SVG vectorization tooling end to end

## 🌀 Open source — loops I've set spinning

- **[limitly](https://github.com/adasarpan404/limitly)** — distributed rate limiter, 6 frameworks, 4 storage backends, **20K+ req/sec** on a single Redis node at p95 < 5ms. `npm install limitly`
- **[stl-javascript](https://github.com/adasarpan404/stl-javascript)** — core data structures (stacks, queues, segment trees, BSTs) for JS, built for teaching and lightweight production use
- Contributor, [OpenFeature.dev](https://openfeature.dev) — PHP onboarding docs

## 🌀 Philosophy corner — Kafka & Nietzsche, ported to prod

> "From a certain point onward there is no longer any turning back. That is the point that must be reached."
> — Franz Kafka
>
> Also known as: the point you `git push --force` and accept your fate.

> "I am a cage, in search of a bird."
> — Franz Kafka
>
> Also known as: a Kubernetes pod, in search of a process that won't crash-loop.

> "One morning Gregor Samsa woke to find himself transformed in his bed into a horrible vermin."
> — Franz Kafka, *The Metamorphosis*
>
> Also known as: what happens when you wake up to 47 failed CI runs and one very angry on-call alert.

> "There are no facts, only interpretations."
> — Friedrich Nietzsche
>
> Also known as: "It's not a bug, it's a feature" — the original source code comment.

> "He who has a why to live can bear almost any how."
> — Friedrich Nietzsche
>
> Also known as: a clear spec can survive even the worst legacy codebase.

> "Whoever fights monsters should see to it that in the process he does not become a monster."
> — Friedrich Nietzsche
>
> Also known as: whoever fights memory leaks should see to it that they don't introduce three more.

🌀 *Every loop here terminates — eventually, probably, citation needed.*

## 🌀 How I work

| Problem | Tools |
|---|---|
| High-throughput backends | Node.js, Express, Fastify, REST, WebSockets, microservices |
| State that has to survive load | MongoDB, PostgreSQL, Redis (Lua scripts, Pub/Sub, cache-aside) |
| Moving data without losing it | Bull/BullMQ, Redis Pub/Sub, MongoDB Change Streams, event-driven design |
| Shipping without breaking prod | AWS (Lambda, SQS, ECS, S3, CloudWatch, ELB), Docker, Kubernetes, GitHub Actions |
| Learning right now | Go (concurrency), Rust (memory safety), distributed systems design |

## 🌀 Writing

Field notes on backend systems — Redis internals, rate limiting tradeoffs, replication, partitioning. **[Read on Hashnode →](https://adasarpan.hashnode.dev/)**

## Education

B.Tech, Computer Science & Engineering — Dr. A.P.J. Abdul Kalam Technical University (2018–2022)

---

📫 [dasarpan471@gmail.com](mailto:dasarpan471@gmail.com) · 🐙 [github.com/adasarpan404](https://github.com/adasarpan404)
