### Hi, I'm Joël 👋

I'm a software engineer who likes to understand systems all the way down — and the systems I find most interesting are the ones money moves through. What actually happens when a payment times out? How do you prove a balance is right, years later? Why does settlement arrive a day after the customer was told "success"?

I build things to answer those questions. This is where they live.

---

#### 🧾 What I'm building

**[KORA Core](https://github.com/Geekers-Joel237/kora-core)** — an open-source digital wallet core, built in public.
My long-running project: a wallet engine for Mobile Money and card-ready neobanks, designed around everything that goes wrong in real payment systems — unstable networks, late or duplicate provider callbacks, next-day settlement, audits.
An append-only double-entry ledger, a payment lifecycle with an explicit `UNKNOWN` state, funds holds, and an [ADR](https://github.com/Geekers-Joel237/kora-core/tree/main/docs/adr) for every decision — including the ones that went wrong. Next on the [roadmap](https://github.com/Geekers-Joel237/kora-core/blob/main/ROADMAP.md): idempotency, a transactional outbox on Kafka, reconciliation, and eventually an AI layer for payment operations that can investigate and explain, but never move money.

#### 🧩 Things I've built

| Project | What it is | Stack |
| --- | --- | --- |
| [battle-royale-des-mots](https://github.com/Geekers-Joel237/battle-royale-des-mots) | Real-time multiplayer word game — up to 50 players per arena, survival and score-attack modes | Java 21 · Spring WebSocket · JavaFX · DDD / Hexagonal |
| [weline-backend](https://github.com/Geekers-Joel237/weline-backend) · [mobile](https://github.com/Geekers-Joel237/weline-mobile) | Virtual queue system built over a weekend: OTP sign-in, digital tickets, agent console | Java · Spring Boot · PostgreSQL · Redis · React Native |

#### 🔭 What I'm exploring

Event-driven systems with Kafka and Kafka Streams · Go and Scala where they earn their place · AWS and Kubernetes · how LLMs can help operate financial systems safely.

I keep my study plan in the open: [FIE-docs](https://github.com/Geekers-Joel237/FIE-docs), a structured curriculum for financial infrastructure engineering.

#### 🛠️ How I like to build

Java and Spring Boot are home. I care about clean boundaries (hexagonal architecture, DDD), tests that run against real databases, and writing down why — not just what.

#### ✍️ Writing

I write about what I learn while building, on [Substack](https://geekersjoel237.substack.com):
[The transaction state machine in payment systems](https://geekersjoel237.substack.com/p/the-transaction-state-machine-in) ·
[Why fintech systems must use a double-entry ledger](https://geekersjoel237.substack.com/p/why-fintech-systems-must-use-a-double)

[LinkedIn](https://www.linkedin.com/in/geekers-joel237/) · [Substack](https://geekersjoel237.substack.com)
