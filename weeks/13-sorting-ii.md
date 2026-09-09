# Week 13 — Sorting II

> Syllabus (TR): *Sıralama*

**Previous:** [Week 12](12-sorting-i.md) · **Next:** [Week 14](14-graph-algorithms.md)

## Goals
- Parallelize quicksort and sample sort.

## Key concepts
- **Parallel quicksort**: the pivot selection problem, shared address space and message passing versions.
- **Bucket sort** and **sample sort** — sample to pick splitters, then bucket in one all-to-all.
- Why sample sort is the practical choice for distributed memory.
- Load balance depends entirely on splitter quality.

## Reading

- [Grama — Ch. 9 — Sorting](../resources/slides/grama-chap09-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Implement sample sort in MPI and measure the load imbalance

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

---

Your own notes for this week go in `terms/<your-term>/notes/week-13.md`, not here.
This file is the shared plan — improve it if the course changes, but keep it general.
