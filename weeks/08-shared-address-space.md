# Week 8 — Programming Shared Address Space Platforms

> Syllabus (TR): *Paylaşılan Adres Uzay Platformlarında Programlama*

**Previous:** [Week 7](07-message-passing.md) · **Next:** [Week 9](09-midterm.md)

## Goals
- Write a correct multithreaded program with POSIX threads or OpenMP.

## Key concepts
- Threads vs. processes; the shared address space.
- **Pthreads**: `pthread_create`, `pthread_join`, mutexes, condition variables.
- **Race conditions**, critical sections, deadlock; the four Coffman conditions.
- **OpenMP**: `#pragma omp parallel for`, `private`/`shared`, `reduction`, `critical`, `atomic`, `barrier`.
- Scheduling clauses: static, dynamic, guided.
- **False sharing** — two threads writing to the same cache line.

## Reading

- [Grama — Ch. 6 — Programming Shared Address Space Platforms](../resources/slides/grama-chap06-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Extend [`labs/shared-memory/mythread.c`](../labs/shared-memory/mythread.c) with a mutex-protected counter
- [ ] Parallelize [`labs/matrix-multiplication/matrix_multiply.c`](../labs/matrix-multiplication/matrix_multiply.c) with OpenMP and measure the speedup

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

---

Your own notes for this week go in `terms/<your-term>/notes/week-08.md`, not here.
This file is the shared plan — improve it if the course changes, but keep it general.
