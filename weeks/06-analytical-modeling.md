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

- [Grama — Ch. 5 — Analytical Modeling of Parallel Programs](../resources/slides/grama-chap05-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Derive the isoefficiency function for a parallel sum reduction

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

---

Your own notes for this week go in `terms/<your-term>/notes/week-06.md`, not here.
This file is the shared plan — improve it if the course changes, but keep it general.
