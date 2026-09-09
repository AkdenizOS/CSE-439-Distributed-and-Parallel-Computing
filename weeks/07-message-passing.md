# Week 7 — Programming Using the Message Passing Paradigm

> Syllabus (TR): *Mesaj Geçiş Paradigmasını Kullanarak Programlama*

**Previous:** [Week 6](06-analytical-modeling.md) · **Next:** [Week 8](08-shared-address-space.md)

## Goals
- Write, compile and run an MPI program.

## Key concepts
- SPMD model; `MPI_Init`, `MPI_Comm_size`, `MPI_Comm_rank`, `MPI_Finalize`.
- **Blocking** `MPI_Send`/`MPI_Recv` and deadlock; the ordering trap with even/odd ranks.
- **Non-blocking** `MPI_Isend`/`MPI_Irecv` + `MPI_Wait` to overlap communication and computation.
- Collectives: `MPI_Bcast`, `MPI_Reduce`, `MPI_Allreduce`, `MPI_Scatter`, `MPI_Gather`, `MPI_Alltoall`, `MPI_Barrier`.
- Communicators, groups, topologies (`MPI_Cart_create`).
- `mpicc prog.c -o prog && mpirun -np 4 ./prog`

## Reading

- [Grama — Ch. 7 — Programming Message Passing Platforms](../resources/slides/grama-chap07-slides.pdf) — the authors' own slides for this chapter
- Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed. — the book itself is not in this repository

## Practice
- [ ] Build every program in [`labs/mpi/`](../labs/mpi/) and run at 1, 2, 4, 8 processes
- [ ] Write a deadlocking send/recv pair, then fix it three different ways

## Checklist
- [ ] Lecture attended
- [ ] Lab done
- [ ] Code compiles and runs

---

Your own notes for this week go in `terms/<your-term>/notes/week-07.md`, not here.
This file is the shared plan — improve it if the course changes, but keep it general.
