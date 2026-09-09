# Week 10 — Dense Matrix Algorithms I

> Syllabus (TR): *Yoğun Matris Algoritmaları*

**Previous:** [Week 9](09-midterm.md) · **Next:** [Week 11](11-dense-matrix-ii.md)

## Goals
- Parallelize matrix-vector and matrix-matrix multiplication.

## Key concepts
- Matrix-vector multiplication: rowwise vs. columnwise vs. 2-D block striping.
- Matrix-matrix multiplication: the simple 2-D block algorithm, `Θ(n³/p)` computation.
- **Cannon's algorithm** — memory-efficient, systematic shifts.
- The DNS algorithm using `n³` processes.
- Data locality: why loop order changes runtime by an order of magnitude — see [`labs/matrix-multiplication/spacial-locality.pdf`](../labs/matrix-multiplication/spacial-locality.pdf).

## Reading

- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the syllabus's textbook, **not in this repository**

## Practice
- [ ] Reproduce the measurements in [`labs/matrix-multiplication/`](../labs/matrix-multiplication/) and explain the loop-order effect

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

## My notes

<!-- Lecture: what was actually covered. -->

<!-- Derivations: speedup, efficiency, isoefficiency. -->

<!-- Questions to ask. -->

<!-- Exam-worthy: cost formulas, topology metrics. -->
