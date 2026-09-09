# Week 1 — Introduction to Parallel Programming

> Syllabus (TR): *Paralel Programlamaya Giriş*

**Next:** [Week 2](02-platforms.md)

## Goals
- Say why parallelism is needed and what limits its payoff.

## Key concepts
- Real vs. apparent parallelism (concurrency vs. true parallelism).
- Motivation: clock speeds stopped scaling, core counts did not.
- **Speedup** `S = T₁/T_p`, **efficiency** `E = S/p`.
- **Amdahl's law**: with a serial fraction `f`, `S ≤ 1/f` no matter how many processors.
- **Gustafson's law**: scale the problem with the machine and the picture improves.
- Where parallel computing runs: embedded devices, laptops, supercomputers, data centres.

## Reading

- [Grama — Ch. 1 — Introduction](../resources/slides/grama-chap01-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Compute the maximum speedup for f = 0.1, 0.05, 0.01

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

## My notes

<!-- Lecture: what was actually covered. -->

<!-- Derivations: speedup, efficiency, isoefficiency. -->

<!-- Questions to ask. -->

<!-- Exam-worthy: cost formulas, topology metrics. -->
