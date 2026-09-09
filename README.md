# CSE 439 — Distributed and Parallel Computing

Akdeniz University · Computer Engineering (English) · Semester 7 · 6 ECTS

**An open study archive for this course.** A week-by-week plan built from the
official syllabus, plus working MPI and pthreads lab code you can compile and run.

## Grading

| Component | Count | Weight |
|-----------|-------|--------|
| Midterm | 1 | 30% |
| Assignments | 5 | 20% |
| Final | 1 | 50% |

Five assignments — the highest assignment count of any course this semester.

## Weekly plan

| # | Topic | Note |
|---|-------|------|
| 1 | Introduction to parallel programming | [weeks/01](weeks/01-introduction.md) |
| 2 | Parallel programming platforms | [weeks/02](weeks/02-platforms.md) |
| 3 | Principles of parallel algorithm design | [weeks/03](weeks/03-algorithm-design.md) |
| 4 | Basic communication operations I | [weeks/04](weeks/04-communication-i.md) |
| 5 | Basic communication operations II | [weeks/05](weeks/05-communication-ii.md) |
| 6 | Analytical modeling of parallel programs | [weeks/06](weeks/06-analytical-modeling.md) |
| 7 | Programming with message passing (MPI) | [weeks/07](weeks/07-message-passing.md) |
| 8 | Shared address space platforms | [weeks/08](weeks/08-shared-address-space.md) |
| 9 | Midterm | [weeks/09](weeks/09-midterm.md) |
| 10 | Dense matrix algorithms I | [weeks/10](weeks/10-dense-matrix-i.md) |
| 11 | Dense matrix algorithms II | [weeks/11](weeks/11-dense-matrix-ii.md) |
| 12 | Sorting I | [weeks/12](weeks/12-sorting-i.md) |
| 13 | Sorting II | [weeks/13](weeks/13-sorting-ii.md) |
| 14 | Graph algorithms | [weeks/14](weeks/14-graph-algorithms.md) |

## How to study with this repository

**1. Open the week you are on** in [`weeks/`](weeks/) — goals, concepts with their
actual cost formulas, and a practice list.

**2. This course is learned by running code, not by reading.** Every week's
practice list points at something in [`labs/`](labs/) to build and run.

```bash
# MPI
mpicc labs/mpi/openmpi_hello.c -o hello && mpirun -np 4 ./hello

# pthreads
gcc labs/shared-memory/mythread.c -o mythread -lpthread && ./mythread

# matrix multiplication, with the timing harness
cd labs/matrix-multiplication && ./test.sh
```

Install MPI first: `brew install open-mpi` on macOS, `apt install libopenmpi-dev
openmpi-bin` on Debian/Ubuntu.

**3. Measure everything.** The exam asks for speedup, efficiency and isoefficiency,
so get in the habit of timing at 1, 2, 4 and 8 processes and computing
`S = T₁/T_p` and `E = S/p` yourself.

**4. Write under `## My notes`** at the bottom of each week note.

## Labs

| Path | What it is |
|------|-----------|
| [`labs/mpi/`](labs/mpi/) | Hello world, send/receive, scatter, find-max — the MPI starting points |
| [`labs/shared-memory/`](labs/shared-memory/) | A pthreads example |
| [`labs/matrix-multiplication/`](labs/matrix-multiplication/) | Matrix multiply with a timing script, a visualizer, results, and a write-up on spatial locality |
| [`labs/missing-numbers/`](labs/missing-numbers/) | A standalone exercise |

Compiled binaries are ignored by git — build them yourself.

## Worked examples

[`terms/2023-2024-spring/`](terms/2023-2024-spring/) holds a previous student's two
homeworks and midterm project from when the course was coded CSE 440. The midterm
report — parallel 5000×5000 matrix multiplication in MPI, with speedup and
efficiency measured against a single-processor baseline — is the clearest model of
what the course expects a report to look like.

## Textbook

Grama, Gupta, Karypis & Kumar, *Introduction to Parallel Computing*, 2nd ed.,
Addison-Wesley. **Not in this repository.** It is the syllabus's only cited source
and the week notes follow its structure.

## Layout

| Path | What it holds |
|------|---------------|
| [`weeks/`](weeks/) | The study plan, one note per week |
| [`docs/`](docs/) | Syllabus summary, glossary |
| [`labs/`](labs/) | Lab code, kept working |
| [`terms/`](terms/) | One folder per cohort — including a previous student's CSE 440 coursework |
| [`resources/`](resources/) | Syllabus PDF |

## Contributing

Create `terms/<YYYY>-<YYYY>-<term>/` with a `README.md` naming the instructor and
dates, and put your assignments and notes there. Keep `weeks/` and `docs/` general.
