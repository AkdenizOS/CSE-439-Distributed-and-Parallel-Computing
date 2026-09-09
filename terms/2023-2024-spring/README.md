# Spring 2023-2024

Coursework by **Mustafa Arınmış**, taken when the course was coded **CSE 440
Parallel Programming**. Attribution comes from the reports themselves — he signed
`hw2/README.md` and dated the midterm report.

| Folder | What it is |
|--------|-----------|
| `hw1/` | Matrix multiplication with a transposed second matrix to improve cache locality, plus a timing harness (`test.sh`), a plotting script, measured results, and a write-up on spatial locality |
| `hw2/` | *Efficient Calculation of Pi via Multithreading* — a final report with pthreads code, a Taylor series derivation, and a performance plot |
| `midterm/` | Parallel matrix multiplication of 5000×5000 matrices with MS-MPI, loading operands from binary files. Includes a benchmark script, a matrix generator, a speedup/efficiency plot, and the full report |

The midterm report is worth reading before writing your own: it states the
objective, the optimizations applied (row-major access, minimizing inter-process
communication), how execution time was measured with `MPI_Wtime()`, and evaluates
speedup and efficiency against a single-processor baseline. That is the structure
the course expects.

Read these as worked examples, not as answers to hand in.

## Relationship to `labs/`

`hw1/` and [`labs/matrix-multiplication/`](../../labs/matrix-multiplication/) look
alike but the programs differ: this one transposes matrix B for cache locality, the
lab version uses pthreads with a `WorkerArgs` struct. Both are worth reading — they
are two different approaches to the same problem.
