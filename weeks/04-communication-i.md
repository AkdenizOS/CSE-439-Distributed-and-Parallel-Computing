# Week 4 — Basic Communication Operations I

> Syllabus (TR): *Temel İletişim İşlemleri*

**Previous:** [Week 3](03-algorithm-design.md) · **Next:** [Week 5](05-communication-ii.md)

## Goals
- Implement and cost one-to-all and all-to-one collective operations.

## Key concepts
- **One-to-all broadcast** and **all-to-one reduction** — recursive doubling.
- Cost model `t_comm = t_s + m·t_w`: startup latency plus per-word transfer.
- On a hypercube: broadcast in `log p` steps, cost `(t_s + m t_w) log p`.
- Ring and mesh variants and why the hypercube is the reference topology.

## Reading

- [Grama — Ch. 4 — Basic Communication Operations](../resources/slides/grama-chap04-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Trace a broadcast on a 3-dimensional hypercube, step by step
- [ ] Read [`labs/mpi/openmpi_hello.c`](../labs/mpi/openmpi_hello.c) and [`send_recieve.c`](../labs/mpi/send_recieve.c)

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

## My notes

<!-- Lecture: what was actually covered. -->

<!-- Derivations: speedup, efficiency, isoefficiency. -->

<!-- Questions to ask. -->

<!-- Exam-worthy: cost formulas, topology metrics. -->
