# Week 6 — Analytical Modeling of Parallel Programs

> Syllabus (TR): *Paralel Programların Analitik Modellenmesi*

**Previous:** [Week 5](05-communication-ii.md) · **Next:** [Week 7](07-message-passing.md)

## Goals
- Compute speedup, efficiency, cost and isoefficiency for a parallel algorithm.

## Key concepts
- Sources of **overhead**: interprocess communication, idling, excess computation.
- `T_o = p·T_p − T_s` — the total overhead function.
- **Cost optimality**: `p·T_p = Θ(T_s)`.
- **Scalability** and the **isoefficiency function**: how fast the problem must grow with `p` to hold efficiency constant.
- Effect of granularity; the minimum execution time and the minimum cost-optimal time.
- Superlinear speedup and why it is usually a cache effect.

## Reading

- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the syllabus's textbook, **not in this repository**

## Practice
- [ ] Derive the isoefficiency function for a parallel sum reduction

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

## My notes

<!-- Lecture: what was actually covered. -->

<!-- Derivations: speedup, efficiency, isoefficiency. -->

<!-- Questions to ask. -->

<!-- Exam-worthy: cost formulas, topology metrics. -->
