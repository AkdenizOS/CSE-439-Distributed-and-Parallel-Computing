# Week 5 — Basic Communication Operations II

> Syllabus (TR): *Temel İletişim İşlemleri*

**Previous:** [Week 4](04-communication-i.md) · **Next:** [Week 6](06-analytical-modeling.md)

## Goals
- Implement and cost all-to-all, scatter, gather and prefix operations.

## Key concepts
- **All-to-all broadcast** and reduction.
- **All-reduce** and **prefix sum (scan)**.
- **Scatter** (one-to-all personalized) and **gather**.
- All-to-all personalized communication (total exchange).
- Circular shift. Improving speed by splitting and routing messages in parts.

## Reading

- [Grama — Ch. 4 — Basic Communication Operations](../resources/slides/grama-chap04-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Read and run [`labs/mpi/scatter.c`](../labs/mpi/scatter.c) and [`find_max.c`](../labs/mpi/find_max.c)
- [ ] Derive the cost of all-to-all broadcast on a hypercube

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

---

Your own notes for this week go in `terms/<your-term>/notes/week-05.md`, not here.
This file is the shared plan — improve it if the course changes, but keep it general.
