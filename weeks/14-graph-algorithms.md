# Week 14 — Graph Algorithms

> Syllabus (TR): *Çizge Algoritmaları*

**Previous:** [Week 13](13-sorting-ii.md)

## Goals
- Parallelize MST, shortest path and connected components.

## Key concepts
- Sparse graph representations for parallel machines.
- **Prim's MST** parallelized by partitioning the vertex set.
- **Dijkstra** single-source and the 1-D block mapping; **Floyd-Warshall** all-pairs with 2-D block mapping.
- Connected components by partitioning and merging spanning forests.
- Parallel BFS and the frontier expansion problem.

## Reading

- [Grama — Ch. 10 — Graph Algorithms](../resources/slides/grama-chap10-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Implement parallel Floyd-Warshall in MPI

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

---

Your own notes for this week go in `terms/<your-term>/notes/week-14.md`, not here.
This file is the shared plan — improve it if the course changes, but keep it general.
