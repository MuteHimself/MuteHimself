### Omar Mahmoud Hassan

AI Engineer & Game Developer — Founder of [Junkhorse Studios](https://www.linkedin.com/company/junkhorse/), a game and software development studio building original, story-driven games.

---

**Featured: [MuteOS](https://github.com/mutehimself/MuteOS)**

A multi-level feedback queue scheduler built inside [Theseus OS](https://github.com/theseus-os/Theseus), a Rust research operating system.

- Designed and implemented an MLFQ scheduler from scratch — priority levels, CPU-time-based demotion, starvation-proof boosting, wired into priority inheritance.
- Measured a ~2x reduction in interactive-task latency versus round-robin (406ms vs. 772ms avg), under a headless benchmark built for the comparison.
- Booted it end-to-end: full SMP bring-up, no panics.
- Opened upstream: [theseus-os/Theseus#1117](https://github.com/theseus-os/Theseus/pull/1117).
