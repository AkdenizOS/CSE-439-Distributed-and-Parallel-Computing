# Week 2 — Parallel Programming Platforms

> Syllabus (TR): *Paralel Programlama Platformları*

**Previous:** [Week 1](01-introduction.md) · **Next:** [Week 3](03-algorithm-design.md)

## Goals
- Classify a machine by its control and memory architecture.

## Key concepts
- **Flynn's taxonomy**: SISD, SIMD, MISD, MIMD.
- **Shared address space** (UMA/NUMA) vs. **message passing** (distributed memory).
- Cache coherence, false sharing.
- Interconnection networks: bus, crossbar, mesh, tree, **hypercube**.
- Network metrics: diameter, bisection width, arc connectivity, cost.
- The hypercube: `p = 2^d` nodes, diameter `d`, bisection width `p/2` — the syllabus singles it out.

## Reading

- [Grama — Ch. 2 — Parallel Programming Platforms](../resources/slides/grama-chap02-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Compute diameter and bisection width for mesh, tree and hypercube at p = 16
- [ ] Run [`labs/shared-memory/mythread.c`](../labs/shared-memory/mythread.c) and read what it does

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

---

Your own notes for this week go in `terms/<your-term>/notes/week-02.md`, not here.
This file is the shared plan — improve it if the course changes, but keep it general.
